<p align="center">
  <h1 align="center">🌐 Gemini & Xbox DNS Setup</h1>
  <p align="center">Быстрая настройка DoH / DoT профилей для обхода региональных ограничений Google Gemini и сервисов Xbox.</p>
</p>

<p align="center">
  <img src="[https://img.shields.io/badge/DNS-over--HTTPS-2563eb?style=flat-square&logo=cloudflare&logoColor=white](https://img.shields.io/badge/DNS-over--HTTPS-2563eb?style=flat-square&logo=cloudflare&logoColor=white)" alt="DoH" />
  <img src="[https://img.shields.io/badge/Platform-iOS%20%7C%20Android%20%7C%20Windows-10b981?style=flat-square](https://img.shields.io/badge/Platform-iOS%20%7C%20Android%20%7C%20Windows-10b981?style=flat-square)" alt="Platforms" />
  <img src="[https://img.shields.io/badge/Profile-.mobileconfig-f59e0b?style=flat-square&logo=apple&logoColor=white](https://img.shields.io/badge/Profile-.mobileconfig-f59e0b?style=flat-square&logo=apple&logoColor=white)" alt="iOS Profile" />
  <img src="[https://img.shields.io/badge/Status-Verified-06b6d4?style=flat-square](https://img.shields.io/badge/Status-Verified-06b6d4?style=flat-square)" alt="Status" />
</p>

---

## ⚡ Быстрые параметры

| Параметр | Значение |
| :--- | :--- |
| **DoH URL** *(Браузеры / Win 11)* | `[https://xbox-dns.ru/dns-query](https://xbox-dns.ru/dns-query)` |
| **DoT Host** *(Android Private DNS)* | `xbox-dns.ru` |
| **Primary IPv4** | `111.88.96.50` |
| **Secondary IPv4** | `111.88.96.51` |
| **iOS Profile** | [Скачать .mobileconfig](http://xbox-dns.ru/ios/xbox-dns.mobileconfig) |

---

## 📱 Мобильные устройства

<details open>
<summary><b>🍏 iOS (iPhone / iPad) — через профиль конфигурации</b></summary>
<br>

> [!IMPORTANT]
> Загрузку необходимо выполнять строго через **Safari**. Сторонние браузеры (Chrome, Яндекс) не имеют доступа к установке профилей iOS.

1. Откройте в Safari прямую ссылку: [xbox-dns.mobileconfig](http://xbox-dns.ru/ios/xbox-dns.mobileconfig).
2. Нажмите **Разрешить** во всплывающем окне загрузки.
3. Перейдите в **Настройки** устройства — сверху появится пункт **«Профиль загружен»**.
4. Нажмите **Установить** в верхнем правом углу и введите код-пароль устройства.
</details>

<details>
<summary><b>🤖 Android (9+) — Частный DNS</b></summary>
<br>

1. Перейдите в **Настройки** → **Подключения** (или **Сеть и интернет**).
2. Откройте пункт **«Другие настройки»** → **«Частный DNS»** (Private DNS).
3. Выберите **«Имя хоста поставщика частного DNS»**.
4. Введите хост: `xbox-dns.ru`
5. Нажмите **Сохранить**.
</details>

---

## 💻 Компьютеры и браузеры

<details>
<summary><b>🌐 Настройка только в браузере (Chromium / Firefox)</b></summary>
<br>

> [!NOTE]
> Метод перенаправляет только браузерные запросы к Gemini, не затрагивая трафик остальных программ и пинг в играх.

* **Chrome / Edge / Яндекс.Браузер / Opera:**
  1. **Настройки** → **Конфиденциальность и безопасность** → **Безопасность**.
  2. Включите **«Использовать безопасный DNS-сервер»**.
  3. Выберите пункт **«С другим поставщиком»** и укажите: `[https://xbox-dns.ru/dns-query](https://xbox-dns.ru/dns-query)`

* **Mozilla Firefox:**
  1. **Настройки** → **Приватность и защита** → блок **«DNS через HTTPS»**.
  2. Выберите режим **«Максимальная защита»**.
  3. В выпадающем меню выберите **«По выбору»** и введите URL: `[https://xbox-dns.ru/dns-query](https://xbox-dns.ru/dns-query)`
</details>

<details>
<summary><b>🪟 Windows 11 (Системный DoH)</b></summary>
<br>

1. Откройте **Параметры** (`Win + I`) → **Сеть и Интернет** → выберите активную сеть (**Wi-Fi** или **Ethernet**).
2. В строке **«Назначение DNS-сервера»** нажмите кнопку **«Изменить»**.
3. Переключите тумблер на **Вручную** и активируйте протокол **IPv4**:
   - **Предпочтительный DNS:** `111.88.96.50`
   - **Дополнительный DNS:** `111.88.96.51`
4. В пункте **«Шифрование DNS»** выберите **«Только шифрование (DNS через HTTPS)»** и вставьте: `[https://xbox-dns.ru/dns-query](https://xbox-dns.ru/dns-query)`
5. Нажмите **Сохранить**.
</details>

<details>
<summary><b>🪟 Windows 10 (Классический IPv4)</b></summary>
<br>

1. Нажмите сочетание клавиш `Win + R`, введите `ncpa.cpl` и нажмите **Enter**.
2. Правый клик по активному сетевому адаптеру → **Свойства**.
3. В списке выделите **«IP версии 4 (TCP/IPv4)»** → нажмите **Свойства**.
4. Активируйте пункт **«Использовать следующие адреса DNS-серверов»**:
   - **Основной:** `111.88.96.50`
   - **Альтернативный:** `111.88.96.51`
5. Подтвердите изменения кнопкой **ОК**.
</details>

---

## 🔍 Диагностика

* **Проверка работы:** перейдите на страницу теста [xbox-dns.ru/test](https://xbox-dns.ru/test).
* **Сброс кэша при сбоях (Windows):** выполните в терминале команду `ipconfig /flushdns` и перезапустите браузер.
