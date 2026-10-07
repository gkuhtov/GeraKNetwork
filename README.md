<div align="center">

# ⛩️ GeraK DNS Bypass

### *Direct DoH / DoT Tunneling • Google Gemini & Xbox Network*

<br>

<p align="center">
  <a href="http://xbox-dns.ru/ios/xbox-dns.mobileconfig">
    <img src="https://img.shields.io/badge/iOS_Profile-MobileConfig-000000?style=for-the-badge&logo=apple&logoColor=white" alt="iOS Profile" />
  </a>
  <img src="https://img.shields.io/badge/Android-Private_DNS-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android DoT" />
  <img src="https://img.shields.io/badge/Desktop-DoH_Secure-2563EB?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Desktop DoH" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Zero--Lag_Ping-Pass-success?style=flat-square" alt="Zero Lag" />
  <img src="https://img.shields.io/badge/Encrypted-TLS_1.3-blueviolet?style=flat-square" alt="TLS" />
  <img src="https://img.shields.io/badge/Direct_Route-No_VPN-orange?style=flat-square" alt="No VPN" />
</p>

<br>

> Легковесный метод восстановить стабильный доступ к **Google Gemini** и сетевой инфраструктуре **Xbox**  
> без фоновых VPN-клиентов, перегрузки сетевых интерфейсов и потери игрового пинга.

<br>

---

<br>

### ⚡ Quick Endpoints Matrix

| Тип подключения | Протокол | Параметр / Значение |
| :--- | :---: | :--- |
| **Браузеры / Windows 11** | `DoH` | `https://xbox-dns.ru/dns-query` |
| **Android Private DNS** | `DoT` | `xbox-dns.ru` |
| **Основной IPv4** | `DNS` | `111.88.96.50` |
| **Дополнительный IPv4** | `DNS` | `111.88.96.51` |
| **Готовый профиль Apple** | `.mobileconfig` | [📥 Скачать конфигурацию](http://xbox-dns.ru/ios/xbox-dns.mobileconfig) |

<br>

---

<br>

## 📱 Mobile Platforms

</div>

<details open>
<summary><h3>🍏 Apple iOS & iPadOS (Установка в 1 клик)</h3></summary>
<br>

> ⚠️ **Важно:** загружайте профиль строго через системный браузер **Safari**. Сторонние браузеры не могут передавать профили в систему iOS.

1. Откройте прямую ссылку в **Safari**: [xbox-dns.mobileconfig](http://xbox-dns.ru/ios/xbox-dns.mobileconfig)
2. В появившемся окне нажмите **«Разрешить»**.
3. Перейдите в **«Настройки»** iPhone/iPad — под вашим именем появится плашка **«Профиль загружен»**.
4. Нажмите **«Установить»** в правом верхнем углу и подтвердите действие код-паролем.

</details>

<details>
<summary><h3>🤖 Android OS (Версия 9.0+)</h3></summary>
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

## 💻 Desktop Systems

</div>

<details open>
<summary><h3>🌐 Изолированный режим в браузере (Chromium & Firefox)</h3></summary>
<br>

> 💡 **Идеальный вариант:** безопасный DNS включается только внутри браузера для Gemini, не трогая трафик игр, Discord и других программ.

* **Chromium (Chrome, Яндекс.Браузер, Edge, Brave, Opera):**
  1. Перейдите в **Настройки** ➔ **Конфиденциальность и безопасность** ➔ **Безопасность**.
  2. Включите тумблер **«Использовать безопасный DNS-сервер»**.
  3. Выберите вариант **«С другим поставщиком»** и вставьте
