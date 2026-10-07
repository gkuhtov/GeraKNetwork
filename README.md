<div align="center">

# ⛩️ GeraK DNS Bypass

### Direct DoH / DoT Tunneling • Google Gemini & Xbox Network

<br>

<p align="center">
  <a href="http://xbox-dns.ru/ios/xbox-dns.mobileconfig">
    <img src="https://img.shields.io/badge/iOS-MobileConfig-000000?style=for-the-badge&logo=apple&logoColor=white" alt="iOS Profile" />
  </a>
  <img src="https://img.shields.io/badge/Android-Private_DNS-059669?style=for-the-badge&logo=android&logoColor=white" alt="Android DoT" />
  <img src="https://img.shields.io/badge/Windows-DoH_Tunnel-2563EB?style=for-the-badge&logo=windows&logoColor=white" alt="Windows DoH" />
  <img src="https://img.shields.io/badge/Browsers-Secure_DNS-D97706?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Browsers" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PING-0ms_Loss-10B981?style=flat-square" alt="Zero Lag" />
  <img src="https://img.shields.io/badge/CIPHER-TLS_1.3-6366F1?style=flat-square" alt="TLS" />
  <img src="https://img.shields.io/badge/ROUTE-Direct_No_VPN-EC4899?style=flat-square" alt="No VPN" />
</p>

<br>

> ⚡ **Zero-Overhead Routing**  
> Нативное восстановление доступа к веб-клиенту **Google Gemini** и сервисам **Xbox**  
> без фоновых VPN-клиентов, перегрузки сетевых интерфейсов и потери игрового пинга.

<br>

---

<br>

### ⚡ Быстрые параметры подключения

| Интерфейс | Тип | Адрес / Хост |
| :---: | :---: | :---: |
| **Браузеры и Windows 11** | `DoH` | `https://xbox-dns.ru/dns-query` |
| **Android (Частный DNS)** | `DoT` | `xbox-dns.ru` |
| **Основной шлюз (IPv4)** | `DNS` | `111.88.96.50` |
| **Резервный шлюз (IPv4)** | `DNS` | `111.88.96.51` |
| **Готовый профиль Apple** | `.mobileconfig` | [📥 Скачать конфигурацию](http://xbox-dns.ru/ios/xbox-dns.mobileconfig) |

<br>

---

<br>

## 📱 Мобильные платформы

</div>

<br>

### 🍏 Apple iOS и iPadOS

> ⚠️ **Важно:** выполняйте загрузку строго через встроенный браузер **Safari** — WebKit передает файл напрямую в системный менеджер профилей Apple.

* **[01]** Откройте в Safari ссылку: [xbox-dns.mobileconfig](http://xbox-dns.ru/ios/xbox-dns.mobileconfig)
* **[02]** Во всплывающем окне подтвердите загрузку кнопкой **«Разрешить»**
* **[03]** Откройте системные **«Настройки»** — сверху появится баннер **«Профиль загружен»**
* **[04]** Нажмите **«Установить»** в правом верхнем углу и введите код-пароль

<br>

### 🤖 Android OS (Версия 9.0 и новее)

* **[01]** Откройте **«Настройки»** -> **«Подключения»** *(или «Сеть и интернет»)*
* **[02]** Перейдите в **«Другие настройки»** -> **«Частный DNS»** *(Private DNS)*
* **[03]** Переключите режим на **«Имя хоста поставщика частного DNS»**
* **[04]** Введите хост: `xbox-dns.ru`
* **[05]** Нажмите кнопку **«Сохранить»**

<br>

<div align="center">

---

<br>

## 💻 Компьютеры и ноутбуки

</div>

<br>

### 🌐 Изолированный режим в браузере (Chrome / Firefox / Edge / Yandex)

> 💡 **Изолированный маршрут:** шифрованный DNS действует исключительно внутри браузера для Gemini. Трафик системы, Discord, Telegram и онлайн-игр остаётся прямым и не теряет в скорости.

<br>

#### 🦊 Mozilla Firefox
* **[01]** Откройте **Настройки** -> **Приватность и защита** -> блок **«DNS через HTTPS»**
* **[02]** Активируйте режим **«Максимальная защита»**
* **[03]** В выпадающем меню выберите **«По выбору»** и укажите URL: `https://xbox-dns.ru/dns-query`

<br>

#### 🌐 Chromium-браузеры (Chrome, Яндекс Браузер, Edge, Brave, Opera)
* **[01]** Откройте **Настройки** -> **Конфиденциальность и безопасность** -> **Безопасность**
* **[02]** Включите тумблер **«Использовать безопасный DNS-сервер»**
* **[03]** Выберите пункт **«С другим поставщиком»** и укажите URL: `https://xbox-dns.ru/dns-query`

<br>

### 🪟 Системная настройка Windows

#### 🔹 Windows 11 (Системный DoH — рекомендуется)
* **[01]** Откройте **Параметры** (`Win + I`) -> **Сеть и Интернет** -> выберите активную сеть (**Wi-Fi** или **Ethernet**)
* **[02]** В блоке **«Назначение DNS-сервера»** нажмите кнопку **«Изменить»**
* **[03]** Выберите **«Вручную»** и активируйте протокол **IPv4**:  
  Основной: `111.88.96.50` | Дополнительный: `111.88.96.51`
* **[04]** В строке **«Шифрование DNS»** выберите **«Только шифрование (DNS через HTTPS)»** и вставьте: `https://xbox-dns.ru/dns-query`
* **[05]** Нажмите **«Сохранить»**

<br>

#### 🔹 Windows 10 (Классический IPv4)
* **[01]** Нажмите `Win + R`, выполните команду `ncpa.cpl`
* **[02]** Правый клик по активному адаптеру -> **«Свойства»**
* **[03]** Выделите строку **«IP версии 4 (TCP/IPv4)»** -> **«Свойства»**
* **[04]** Активируйте ручной ввод:  
  Основной: `111.88.96.50` | Альтернативный: `111.88.96.51`
* **[05]** Подтвердите изменения кнопкой **ОК**

<br>

<div align="center">

---

<br>

## 🔍 Проверка и диагностика

</div>

<br>

* 🌐 **Тест подключения:** проверьте статус на официальной странице [xbox-dns.ru/test](https://xbox-dns.ru/test)
* ⚡ **Сброс системного кэша сокетов (Windows):** выполните команду в консоли:
  ```cmd
  ipconfig /flushdns
  ```
  После выполнения команды перезапустите браузер.

<br>

<div align="center">

---

<br>

<sub><b>GeraK Network</b> • Clean Routing & Minimalist Architecture</sub>

</div>
