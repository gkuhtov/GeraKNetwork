<div align="center">

# ⛩️ GeraK DNS Bypass

### *Direct DoH / DoT Tunneling • Google Gemini & Xbox Network*

<br>

<p align="center">
  <a href="http://xbox-dns.ru/ios/xbox-dns.mobileconfig">
    <img src="https://img.shields.io/badge/iOS-MobileConfig-black?style=for-the-badge&logo=apple&logoColor=white" alt="iOS Profile" />
  </a>
  <img src="https://img.shields.io/badge/Android-Private_DNS-059669?style=for-the-badge&logo=android&logoColor=white" alt="Android DoT" />
  <img src="https://img.shields.io/badge/Windows-DoH_Tunnel-2563EB?style=for-the-badge&logo=windows&logoColor=white" alt="Windows DoH" />
  <img src="https://img.shields.io/badge/Browsers-Secure_DNS-D97706?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Browsers" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PING-0ms_Loss-10B981?style=flat-square&logo=speedtest&logoColor=white" alt="Zero Lag" />
  <img src="https://img.shields.io/badge/CIPHER-TLS_1.3-6366F1?style=flat-square&logo=letsencrypt&logoColor=white" alt="TLS" />
  <img src="https://img.shields.io/badge/ROUTE-Direct_No_VPN-EC4899?style=flat-square&logo=cloudflare&logoColor=white" alt="No VPN" />
</p>

<br>

> ⚡ **Zero-Overhead Routing:** нативное восстановление доступа к веб-клиенту **Google Gemini** и экосистеме **Xbox** без запуска фоновых VPN-клиентов, перегрузки сети и просадок FPS/пинга в играх.

<br>

---

<br>

### ⚡ Быстрые параметры подключения

| Интерфейс | Тип | Адрес / Хост |
| :--- | :---: | :--- |
| 🌐 **Браузеры и Windows 11** | `DoH` | `https://xbox-dns.ru/dns-query` |
| 🤖 **Android (Частный DNS)** | `DoT` | `xbox-dns.ru` |
| 🎮 **Основной шлюз (IPv4)** | `DNS` | `111.88.96.50` |
| 🎮 **Резервный шлюз (IPv4)** | `DNS` | `111.88.96.51` |
| 🍏 **Готовый профиль Apple** | `.mobileconfig` | [📥 Скачать конфигурацию](http://xbox-dns.ru/ios/xbox-dns.mobileconfig) |

<br>

---

<br>

## 📱 Мобильные платформы

</div>

<details open>
<summary><h3>🍏 Apple iOS и iPadOS (Установка профиля)</h3></summary>
<br>

> ⚠️ **Важно:** выполняйте загрузку строго через нативный **Safari** — движок WebKit напрямую передаёт конфигурацию в системный установщик iOS.

* **`[01]`** Перейдите в Safari по прямой ссылке: [xbox-dns.mobileconfig](http://xbox-dns.ru/ios/xbox-dns.mobileconfig)
* **`[02]`** Во всплывающем окне подтвердите загрузку кнопкой **«Разрешить»**.
* **`[03]`** Откройте системные **«Настройки»** — сверху появится баннер **«Профиль загружен»**.
* **`[04]`** Нажмите **«Установить»** в правом верхнем углу и подтвердите ввод код-пароля.

</details>

<details>
<summary><h3>🤖 Android OS (Версия 9.0 и новее)</h3></summary>
<br>

* **`[01]`** Откройте системные **«Настройки»** ➔ **«Подключения»** *(или «Сеть и интернет»)*.
* **`[02]`** Перейдите в пункт **«Другие настройки»** ➔ **«Частный DNS»** *(Private DNS)*.
* **`[03]`** Переключите тумблер на **«Имя хоста поставщика частного DNS»**.
* **`[04]`** Укажите адрес:
  ```text
  xbox-dns.ru
  ```
* **`[05]`** Нажмите кнопку **«Сохранить»**.

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

> 💡 **Изолированный туннель:** шифрованный DNS действует исключительно внутри браузера для Gemini. Трафик системы, Discord, Telegram и онлайн-игр остаётся полностью нетронутым.

#### 🦊 Mozilla Firefox
* **`[01]`** Откройте **Настройки** ➔ **Приватность и защита** ➔ секция **«DNS через HTTPS»**.
* **`[02]`** Активируйте режим **«Максимальная защита»**.
* **`[03]`** В выпадающем списке провайдера выберите **«По выбору»** и вставьте URL:
  ```text
  [https://xbox-dns.ru/dns-query](https://xbox-dns.ru/dns-query)
  ```

#### 🌐 Chromium-браузеры (Chrome, Яндекс Браузер, Edge, Brave, Opera)
* **`[01]`** Перейдите в **Настройки** ➔ **Конфиденциальность и безопасность** ➔ **Безопасность**.
* **`[02]`** Включите тумблер **«Использовать безопасный DNS-сервер»**.
* **`[03]`** Отметьте вариант **«С другим поставщиком»** и вставьте URL:
  ```text
  [https://xbox-dns.ru/dns-query](https://xbox-dns.ru/dns-query)
  ```

</details>

<details>
<summary><h3>🪟 Системная настройка Windows</h3></summary>
<br>

<details>
<summary><b>🔹 Windows 11 (Системный DoH — рекомендуется)</b></summary>
<br>

* **`[01]`** Откройте **Параметры** (`Win + I`) ➔ **Сеть и Интернет** ➔ активное подключение (**Wi-Fi** или **Ethernet**).
* **`[02]`** В блоке **«Назначение DNS-сервера»** нажмите кнопку **«Изменить»**.
* **`[03]`** Переключите режим на **«Вручную»** и активируйте протокол **IPv4**:
  * **Предпочтительный DNS:** `111.88.96.50`
  * **Дополнительный DNS:** `111.88.96.51`
* **`[04]`** В строке **«Шифрование DNS»** выберите **«Только шифрование (DNS через HTTPS)»** и вставьте шаблон:
  ```text
  [https://xbox-dns.ru/dns-query](https://xbox-dns.ru/dns-query)
  ```
* **`[05]`** Нажмите **«Сохранить»**.

</details>

<br>

<details>
<summary><b>🔹 Windows 10 (Классический IPv4)</b></summary>
<br>

* **`[01]`** Нажмите сочетание клавиш `Win + R`, введите команду `ncpa.cpl` и нажмите **Enter**.
* **`[02]`** Кликните правой кнопкой мыши по текущему подключению ➔ **«Свойства»**.
* **`[03]`** Выделите строку **«IP версии 4 (TCP/IPv4)»** ➔ нажмите **«Свойства»**.
* **`[04]`** Отметьте пункт **«Использовать следующие адреса DNS-серверов»**:
  * **Основной DNS:** `111.88.96.50`
  * **Альтернативный DNS:** `111.88.96.51`
* **`[05]`** Нажмите **ОК** для сохранения.

</details>

</details>

<br>

<div align="center">

---

<br>

## 🔍 Проверка и диагностика

</div>

* **`[TEST]`** **Статус соединения:** проверьте корректность работы шлюза на странице [xbox-dns.ru/test](https://xbox-dns.ru/test).
* **`[FLUSH]`** **Сброс системного сокет-кэша:** при задержках или старых маршрутах выполните в консоли (CMD / PowerShell):
  ```cmd
  ipconfig /flushdns
  ```
  После выполнения команды перезапустите браузер.

<br>

<div align="center">

---

<sub><b>GeraK Network</b> • Clean Routing & Minimalist Architecture</sub>

</div>
