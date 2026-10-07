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

### 💉 БЕЗ ТОРМОЗОВ И VPN-КОСТЫЛЕЙ

**Чистый проброс маршрутов к Google Gemini и серверам Xbox.**  
Никаких кривых фоновых клиентов, лишней нагрузки на систему и улетевшего в космос пинга.

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

## 📱 МОБИЛЬНЫЕ ПЛАТФОРМЫ

<br>

<img src="https://img.shields.io/badge/APPLE_iOS_%26_iPadOS-Быстрая_установка_профиля-black?style=for-the-badge&logo=apple&logoColor=white" alt="iOS" />

<br><br>

</div>

> ⚠️ **Важно:** выполняйте загрузку строго через встроенный браузер **Safari** — WebKit передает файл напрямую в системный менеджер профилей Apple.

* 🚀 **Загрузка:** Откройте в Safari ссылку: [xbox-dns.mobileconfig](http://xbox-dns.ru/ios/xbox-dns.mobileconfig)
* 📥 **Системный запрос:** Во всплывающем окне подтвердите загрузку кнопкой **«Разрешить»**
* ⚙️ **Профиль:** Откройте системные **«Настройки»** — сверху появится баннер **«Профиль загружен»**
* 🛡️ **Финиш:** Нажмите **«Установить»** в правом верхнем углу и введите код-пароль

<br>

<div align="center">

<img src="https://img.shields.io/badge/ANDROID_OS-Частный_DNS_(9.0%2B)-059669?style=for-the-badge&logo=android&logoColor=white" alt="Android" />

<br><br>

</div>

* 📡 **Сетевой стек:** Откройте **«Настройки»** -> **«Подключения»** *(или «Сеть и интернет»)*
* ⚙️ **Параметры:** Перейдите в **«Другие настройки»** -> **«Частный DNS»** *(Private DNS)*
* 🎛️ **Режим работы:** Переключите тумблер на **«Имя хоста поставщика частного DNS»**
* 🌐 **Ввод адреса:** Укажите хост: `xbox-dns.ru`
* 🛡️ **Финиш:** Нажмите кнопку **«Сохранить»**

<br>

<div align="center">

---

<br>

## 💻 КОМПЬЮТЕРЫ И НОУТБУКИ

<br>

<img src="https://img.shields.io/badge/ВЕБ--БРАУЗЕРЫ-Изолированный_DoH_режим-D97706?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Browsers" />

<br><br>

</div>

> 💡 **Изолированный маршрут:** шифрованный DNS действует исключительно внутри браузера для Gemini. Трафик системы, Discord, Telegram и онлайн-игр остаётся прямым и не теряет в скорости.

<br>

<div align="center">

#### 🦊 Mozilla Firefox

</div>

* 🛡️ **Безопасность:** Откройте **Настройки** -> **Приватность и защита** -> блок **«DNS через HTTPS»**
* ⚡ **Профиль:** Активируйте режим **«Максимальная защита»**
* 🌐 **Кастомный провайдер:** В выпадающем меню выберите **«По выбору»** и укажите URL: `https://xbox-dns.ru/dns-query`

<br>

<div align="center">

#### 🌐 Chromium-браузеры (Chrome, Яндекс Браузер, Edge, Brave, Opera)

</div>

* 🛡️ **Безопасность:** Откройте **Настройки** -> **Конфиденциальность и безопасность** -> **Безопасность**
* ⚡ **Переключатель:** Включите тумблер **«Использовать безопасный DNS-сервер»**
* 🌐 **Кастомный шлюз:** Выберите пункт **«С другим поставщиком»** и укажите URL: `https://xbox-dns.ru/dns-query`

<br>

<div align="center">

---

<br>

<img src="https://img.shields.io/badge/WINDOWS_OS-Системная_конфигурация-2563EB?style=for-the-badge&logo=windows&logoColor=white" alt="Windows" />

<br><br>

#### 🔹 Windows 11 (Системный DoH — рекомендуется)

</div>

* 📡 **Сетевой адаптер:** Откройте **Параметры** (`Win + I`) -> **Сеть и Интернет** -> выберите активную сеть (**Wi-Fi** или **Ethernet**)
* ⚙️ **Конфигурация:** В блоке **«Назначение DNS-сервера»** нажмите кнопку **«Изменить»**
* 🎛️ **Назначение IP:** Выберите **«Вручную»** и активируйте протокол **IPv4**:  
  Основной: `111.88.96.50` | Дополнительный: `111.88.96.51`
* 🔒 **Шифрование:** В строке **«Шифрование DNS»** выберите **«Только шифрование (DNS через HTTPS)»** и вставьте: `https://xbox-dns.ru/dns-query`
* 🛡️ **Финиш:** Нажмите **«Сохранить»**

<br>

<div align="center">

#### 🔹 Windows 10 (Классический IPv4)

</div>

* ⌨️ **Терминал адаптеров:** Нажмите `Win + R`, выполните команду `ncpa.cpl`
* 🖱️ **Контекстное меню:** Правый клик по активному адаптеру -> **«Свойства»**
* 🎛️ **Стек протокола:** Выделите строку **«IP версии 4 (TCP/IPv4)»** -> **«Свойства»**
* 🌐 **DNS-маршруты:** Активируйте ручной ввод:  
  Основной: `111.88.96.50` | Альтернативный: `111.88.96.51`
* 🛡️ **Финиш:** Подтвердите изменения кнопкой **ОК**

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
