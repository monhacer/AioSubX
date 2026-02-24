# 🎨 X-UI Custom Themes

Custom subscription templates for:

- ✅ 3x-ui  
- ✅ tx-ui (TX-ThemeHub)

---

## 🌍 Language

- 🇬🇧 [English](#-english-documentation)
- 🇮🇷 [فارسی](#-مستندات-فارسی)

---

# 📁 Repository Structure

```
.
├── 3x-ui/
│   └── template-name.ejs
└── tx-ui/
    └── template-name.html
```

Each folder contains the template file specific to that panel.

---

# 🇬🇧 English Documentation

## 📌 Overview

This repository provides **custom subscription page templates**.

It does NOT include:

- Panel installation
- Backend service
- Automatic installer
- Standalone system

It only modifies the appearance of the subscription page.

---

# 🔹 Prerequisites

## 1️⃣ For 3x-ui Themes

Before using any theme inside the `3x-ui/` folder, the following project MUST be installed:

👉 https://github.com/dev-ir/XUI-Subscription-Template/

### Why?

- This repository only provides `.ejs` template files.
- The template engine and service system are handled by XUI-Subscription-Template.
- The dvhost service loads and renders the template.
- Without that project, the theme will NOT work.

### Requirements

- XUI-Subscription-Template installed
- dvhost service running
- Template directory available  
  (example: `/opt/DVHOST/views/templates/`)
- Proper server permissions

⚠️ This is NOT a standalone panel.  
It only customizes the subscription UI.

---

## 2️⃣ For tx-ui Themes

Before using any theme inside the `tx-ui/` folder, you must have:

👉 A working tx-ui (TX-ThemeHub based panel)

### Why?

- This repository only provides a custom HTML template.
- The panel system must already be installed.
- The theme only replaces the subscription page design.

### Requirements

- tx-ui installed and working
- Subscription system enabled
- Access to template directory  
  (example: `/etc/x-ui/html/`)
- Custom Subscription Template enabled in panel settings

⚠️ This theme does NOT install tx-ui.  
It only changes the subscription page appearance.

---

# 🔄 Updating a Theme

1. Backup your current template  
2. Replace it with the new version  
3. Restart the related panel service  
4. Verify changes  

---

# ❗ Troubleshooting

If the theme does not load:

- Ensure the required base project is installed
- Verify correct template path
- Make sure related service is running
- Clear browser cache

---

---

# 🇮🇷 مستندات فارسی

## 📌 معرفی

این مخزن شامل قالب‌های سفارشی صفحه اشتراک برای:

- ✅ 3x-ui  
- ✅ tx-ui  

است.

این مخزن شامل نصب پنل یا سیستم اجرایی نیست و فقط ظاهر صفحه اشتراک را تغییر می‌دهد.

---

# 🔹 پیش‌نیازها

## 1️⃣ برای تم‌های 3x-ui

قبل از استفاده از فایل‌های داخل پوشه `3x-ui/`، باید پروژه زیر روی سرور شما نصب شده باشد:

👉 https://github.com/dev-ir/XUI-Subscription-Template/

### چرا؟

- این مخزن فقط فایل قالب `.ejs` را ارائه می‌دهد.
- موتور قالب و سیستم اجرا توسط XUI-Subscription-Template مدیریت می‌شود.
- سرویس dvhost مسئول بارگذاری قالب است.
- بدون نصب این پروژه، تم کار نخواهد کرد.

### موارد مورد نیاز

- نصب بودن XUI-Subscription-Template
- فعال بودن سرویس dvhost
- وجود مسیر قالب  
  (مثال: `/opt/DVHOST/views/templates/`)
- دسترسی مناسب به سرور

⚠️ این تم یک پنل مستقل نیست.  
فقط ظاهر صفحه اشتراک را تغییر می‌دهد.

---

## 2️⃣ برای تم‌های tx-ui

قبل از استفاده از فایل‌های داخل پوشه `tx-ui/` باید:

👉 پنل tx-ui نصب و فعال باشد.

### چرا؟

- این مخزن فقط فایل HTML قالب اشتراک را ارائه می‌دهد.
- خود پنل باید قبلاً نصب شده باشد.
- تم فقط ظاهر صفحه اشتراک را جایگزین می‌کند.

### موارد مورد نیاز

- نصب بودن tx-ui
- فعال بودن سیستم Subscription
- دسترسی به مسیر قالب  
  (مثال: `/etc/x-ui/html/`)
- فعال بودن Custom Template در تنظیمات پنل

⚠️ این تم باعث نصب پنل نمی‌شود.  
فقط ظاهر صفحه اشتراک را تغییر می‌دهد.

---

# 👨‍💻 Maintainer

Maintained by ❤️ aioexp  

📢 Telegram Channel:  
https://t.me/aioexphub
