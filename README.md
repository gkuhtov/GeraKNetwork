<p align="center">
  <h1 align="center">🌐 Gemini & Xbox DNS Setup</h1>
  <p align="center">Быстрая настройка DoH / DoT профилей для обхода региональных ограничений Google Gemini и сервисов Xbox.</p>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/DNS-over--HTTPS-2563eb?style=flat-square&logo=cloudflare&logoColor=white" alt="DoH" />
  <img src="https://img.shields.io/badge/Platform-iOS%20%7C%20Android%20%7C%20Windows-10b981?style=flat-square" alt="Platforms" />
  <img src="https://img.shields.io/badge/Profile-.mobileconfig-f59e0b?style=flat-square&logo=apple&logoColor=white" alt="iOS Profile" />
  <img src="https://img.shields.io/badge/Status-Verified-06b6d4?style=flat-square" alt="Status" />
</p>

---

## ⚡ Быстрые параметры

| Параметр | Значение |
| :--- | :--- |
| **DoH URL** *(Браузеры / Win 11)* | `https://xbox-dns.ru/dns-query` |
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
4. Введите хост:
   ```text
   xbox-dns.ru
