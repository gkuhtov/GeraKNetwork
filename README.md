<div align="center">

# ⛩️ GeraK DNS Bypass

### *Direct DoH / DoT Tunneling • Google Gemini & Xbox Network*

<br>

<p align="center">
  <a href="http://xbox-dns.ru/ios/xbox-dns.mobileconfig">
    <img src="https://img.shields.io/badge/iOS_Профиль-MobileConfig-000000?style=for-the-badge&logo=apple&logoColor=white" alt="iOS Профиль" />
  </a>
  <img src="https://img.shields.io/badge/Android-Частный_DNS-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android DoT" />
  <img src="https://img.shields.io/badge/ПК-Безопасный_DoH-2563EB?style=for-the-badge&logo=windows&logoColor=white" alt="ПК DoH" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Пинг-Без_задержек-success?style=flat-square" alt="Zero Lag" />
  <img src="https://img.shields.io/badge/Шифрование-TLS_1.3-blueviolet?style=flat-square" alt="TLS" />
  <img src="https://img.shields.io/badge/Маршрут-Без_VPN-orange?style=flat-square" alt="Без VPN" />
</p>

<br>

> Легковесный метод восстановить стабильный доступ к **Google Gemini** и сетевой инфраструктуре **Xbox**  
> без фоновых VPN-клиентов, перегрузки сетевых интерфейсов и потери игрового пинга.

<br>

---

<br>

### ⚡ Быстрые параметры подключения

| Тип подключения | Протокол | Параметр / Значение |
| :--- | :---: | :--- |
| **Браузеры / Windows 11** | `DoH` | `https://xbox-dns.ru/dns-query` |
| **Android (Частный DNS)** | `DoT` | `xbox-dns.ru` |
| **Основной IPv4** | `DNS` | `111.88.96.50` |
| **Дополнительный IPv4** | `DNS` | `111.88.96.51` |
| **Готовый профиль Apple** | `.mobileconfig` | [📥 Скачать конфигурацию](http://xbox-dns.ru/ios/xbox-dns.mobileconfig) |

<br>

---

<br>

## 📱 Мобильные платформы

</div>

<details open>
<summary><h3>🍏 Apple iOS и iPadOS (Установка в 1 клик)</h3></summary>
<br>

> ⚠️ **Важно:** загружайте профиль строго через системный браузер **Safari**. Сторонние браузеры не могут передавать профили в систему iOS.

1. Откройте прямую ссылку в **Safari**: [xbox-dns.mobileconfig](http://xbox-dns.ru/ios/xbox-dns.mobileconfig)
2. В появившемся окне нажмите **«Разрешить»**.
3. Перейдите в **«Настройки»** iPhone/iPad — под вашим именем появится плашка **«Профиль загружен»**.
4. Нажмите **«Установить»** в правом верхнем углу и подтвердите действие код-паролем.

</details>

<details>
<summary><h3>🤖 Android (Версия 9.0 и новее)</h3></summary>
<br>

1. Откройте системные **«Настройки»** ➔ **«Подключения»** (или **«Сеть и интернет»**).
2. Перейдите в **«Другие настройки»** ➔ **«Частный DNS»** *(Private DNS)*.
3. Переключите режим на **«Имя хоста поставщика частного DNS»**.
4. Укажите адрес:
   ```text
   xbox-dns.ru
   ```
5. Нажмите кнопку **«Сохранить»**.

</details>

<br>

<div align="center">

---

<br>

## 💻 Компьютеры и ноутбуки

</div>

<details open>
<summary><h3>🌐 Изолированный режим в браузере (Chromium и Firefox)</h3></summary>
<br>

> 💡 **Идеальный вариант:** безопасный DNS включается только внутри браузера для Gemini, не трогая трафик игр, Discord и других программ.

* **Chromium (Chrome, Яндекс Браузер, Edge, Brave, Opera):**
  1. Перейдите в **Настройки** ➔ **Конфиденциальность и безопасность** ➔ **Безопасность**.
  2. Включите тумблер **«Использовать безопасный DNS-сервер»**.
  3. Выберите вариант **«С другим поставщиком»** и вставьте URL:
     ```text
     [https://xbox-dns.ru/dns-query](https://xbox-dns.ru/dns-query)
     ```

* **Mozilla Firefox:**
  1. Откройте **Настройки** ➔ раздел **Приватность и защита** ➔ пункт **«DNS через HTTPS»**.
  2. Выберите режим **«Максимальная защита»**.
  3. В списке поставщиков укажите вариант **«По выбору»** и вставьте URL:
     ```text
    https://xbox-dns.ru/dns-query
     ```

</details>

<details>
<summary><h3>🪟 Системная настройка Windows</h3></summary>
<br>

<details>
<summary><b>🔹 Windows 11 (Системный DoH — рекомендуется)</b></summary>
<br>

1. Откройте **Параметры** (`Win + I`) ➔ **Сеть и Интернет** ➔ выберите активную сеть (**Wi-Fi** или **Ethernet**).
2. В блоке **«Назначение DNS-сервера»** нажмите **«Изменить»**.
3. Переключите режим на **«Вручную»** и активируйте тумблер **IPv4**:
   * **Предпочтительный DNS:** `111.88.96.50`
   * **Дополнительный DNS:** `111.88.96.51`
4. В строке **«Шифрование DNS»** выберите **«Только шифрование (DNS через HTTPS)»** и укажите шаблон:
   ```text
   [https://xbox-dns.ru/dns-query](https://xbox-dns.ru/dns-query)
   ```
5. Сохраните изменения.

</details>

<br>

<details>
<summary><b>🔹 Windows 10 (Классический IPv4)</b></summary>
<br>

1. Нажмите комбинацию `Win + R`, введите команду `ncpa.cpl` и нажмите **Enter**.
2. Кликните правой кнопкой мыши по текущему подключению ➔ **«Свойства»**.
3. Выделите строку **«IP версии 4 (TCP/IPv4)»** ➔ нажмите кнопку **«Свойства»**.
4. Отметьте пункт **«Использовать следующие адреса DNS-серверов»**:
   * **Основной DNS:** `111.88.96.50`
   * **Альтернативный DNS:** `111.88.96.51`
5. Нажмите **ОК** для подтверждения.

</details>

</details>

<br>

<div align="center">

---

<br>

## 🔍 Проверка и диагностика

</div>

* **Тест работоспособности:** проверьте подключение на официальной странице [xbox-dns.ru/test](https://xbox-dns.ru/test).
* **Сброс системного кэша DNS (Windows):** если сохраняются старые маршруты, откройте терминал (PowerShell или CMD) и выполните:
  ```cmd
  ipconfig /flushdns
  ```
  После выполнения перезапустите браузер.

<br>

<div align="center">

---

<sub><b>GeraK Network</b> • Clean Routing & Minimalist Architecture</sub>

</div>
