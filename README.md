# ⛩️ GeraK DNS Bypass

### *Direct DoH / DoT Tunneling • Google Gemini & Xbox Network*

<p align="left">
  <a href="http://xbox-dns.ru/ios/xbox-dns.mobileconfig">
    <img src="https://img.shields.io/badge/iOS-MobileConfig-black?style=for-the-badge&logo=apple&logoColor=white" alt="iOS Profile" />
  </a>
  <img src="https://img.shields.io/badge/Android-Private_DNS-059669?style=for-the-badge&logo=android&logoColor=white" alt="Android DoT" />
  <img src="https://img.shields.io/badge/Windows-DoH_Tunnel-2563EB?style=for-the-badge&logo=windows&logoColor=white" alt="Windows DoH" />
  <img src="https://img.shields.io/badge/Browsers-Secure_DNS-D97706?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Browsers" />
</p>

<p align="left">
  <img src="https://img.shields.io/badge/PING-0ms_Loss-10B981?style=flat-square&logo=speedtest&logoColor=white" alt="Zero Lag" />
  <img src="https://img.shields.io/badge/CIPHER-TLS_1.3-6366F1?style=flat-square&logo=letsencrypt&logoColor=white" alt="TLS" />
  <img src="https://img.shields.io/badge/ROUTE-Direct_No_VPN-EC4899?style=flat-square&logo=cloudflare&logoColor=white" alt="No VPN" />
</p>

> ⚡ **Zero-Overhead Routing:** нативное восстановление доступа к веб-клиенту **Google Gemini** и экосистеме **Xbox** без запуска фоновых VPN-клиентов, перегрузки сети и просадок пинга.

---

### ⚡ Быстрые параметры подключения

| Интерфейс | Тип | Адрес / Хост |
| :--- | :---: | :--- |
| 🌐 **Браузеры и Windows 11** | `DoH` | `https://xbox-dns.ru/dns-query` |
| 🤖 **Android (Частный DNS)** | `DoT` | `xbox-dns.ru` |
| 🎮 **Основной шлюз (IPv4)** | `DNS` | `111.88.96.50` |
| 🎮 **Резервный шлюз (IPv4)** | `DNS` | `111.88.96.51` |
| 🍏 **Готовый профиль Apple** | `.mobileconfig` | [📥 Скачать конфигурацию](http://xbox-dns.ru/ios/xbox-dns.mobileconfig) |

---

## 📱 Мобильные платформы

<details open>
<summary><h3>🍏 Apple iOS и iPadOS (Установка профиля)</h3></summary>

> [!WARNING]
> Загрузку необходимо выполнять строго через системный **Safari** — WebKit передаёт конфигурацию напрямую в системный менеджер профилей iOS.

- ❯ **Загрузка:** перейдите в Safari по прямой ссылке: [xbox-dns.mobileconfig](http://xbox-dns.ru/ios/xbox-dns.mobileconfig)
- ❯ **Разрешение:** во всплывающем окне подтвердите скачивание кнопкой **«Разрешить»**.
- ❯ **Инициализация:** откройте системные **«Настройки»** — сверху появится баннер **«Профиль загружен»**.
- ✔ **Активация:** нажмите **«Установить»** в правом верхнем углу и введите код-пароль.

</details>

<details>
<summary><h3>🤖 Android OS (Версия 9.0 и новее)</h3></summary>

- ❯ **Сетевой стек:** откройте **«Настройки»** ➔ **«Подключения»** *(или «Сеть и интернет»)*.
- ❯ **Параметры:** перейдите в раздел **«Другие настройки»** ➔ **«Частный DNS»** *(Private DNS)*.
- ❯ **Режим работы:** переключите селектор на **«Имя хоста поставщика частного DNS»**.
- ❯ **Хост:** укажите адрес `xbox-dns.ru`
- ✔ **Готово:** нажмите кнопку **«Сохранить»**.

</details>

---

## 💻 Компьютеры и ноутбуки

<details open>
<summary><h3>🌐 Изолированный режим в браузере (Chromium и Firefox)</h3></summary>

> [!TIP]
> Шифрованный DNS действует **исключительно внутри браузера**. Трафик системы, Discord, Telegram и онлайн-игр остаётся прямым и не теряет в скорости.

#### 🦊 Mozilla Firefox
- ❯ **Безопасность:** откройте **Настройки** ➔ **Приватность и защита** ➔ секция **«DNS через HTTPS»**.
- ❯ **Уровень:** активируйте режим **«Максимальная защита»**.
- ✔ **Провайдер:** в списке укажите **«По выбору»** и вставьте URL: `https://xbox-dns.ru/dns-query`

#### 🌐 Chromium-браузеры (Chrome, Яндекс Браузер, Edge, Brave, Opera)
- ❯ **Безопасность:** перейдите в **Настройки** ➔ **Конфиденциальность и безопасность** ➔ **Безопасность**.
- ❯ **Переключатель:** включите тумблер **«Использовать безопасный DNS-сервер»**.
- ✔ **Кастомный шлюз:** выберите вариант **«С другим поставщиком»** и вставьте: `https://xbox-dns.ru/dns-query`

</details>

<details>
<summary><h3>🪟 Системная настройка Windows</h3></summary>

<details>
<summary><b>🔹 Windows 11 (Системный DoH — рекомендуется)</b></summary>

- ❯ **Адаптер:** откройте **Параметры** (`Win + I`) ➔ **Сеть и Интернет** ➔ активное подключение (**Wi-Fi** / **Ethernet**).
- ❯ **Конфигурация:** в блоке **«Назначение DNS-сервера»** нажмите кнопку **«Изменить»**.
- ❯ **Протокол:** выберите **«Вручную»** и активируйте **IPv4**:
  - *Предпочтительный DNS:* `111.88.96.50`
  - *Дополнительный DNS:* `111.88.96.51`
- ✔ **Шифрование:** в поле **«Шифрование DNS»** выберите **«Только шифрование (DNS через HTTPS)»** и задайте: `https://xbox-dns.ru/dns-query`

</details>

<br>

<details>
<summary><b>🔹 Windows 10 (Классический IPv4)</b></summary>

- ❯ **Панель сетей:** нажмите `Win + R`, выполните `ncpa.cpl`.
- ❯ **Интерфейс:** кликните правой кнопкой по текущему адаптеру ➔ **«Свойства»**.
- ❯ **Настройка IP:** выделите строку **«IP версии 4 (TCP/IPv4)»** ➔ **«Свойства»**.
- ✔ **DNS-серверы:** активируйте ручной ввод:
  - *Основной:* `111.88.96.50`
  - *Альтернативный:* `111.88.96.51`

</details>

</details>

---

## 🔍 Проверка и диагностика

- 🌐 **Тест маршрутизации:** проверьте статус на официальной странице [xbox-dns.ru/test](https://xbox-dns.ru/test).
- ⚡ **Сброс системного сокет-кэша:** при задержках выполните команду в консоли (CMD / PowerShell):
  ```cmd
  ipconfig /flushdns
  ```
  После выполнения команды перезапустите браузер.

---

<p align="center">
  <sub><b>GeraK Network</b> • Clean Routing & Minimalist Architecture</sub>
</p>
