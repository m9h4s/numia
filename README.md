# numia
NUMIA: Iran's first native real-time network monitoring &amp; cybersecurity platform. Cross-platform agents (Windows/Linux/macOS), DLP, USB control, centralized management. Built with Python. 🔒 [numia.ir]

# NUMIA: Network Upload Monitoring Intelligence Agent

<div align="center">

![NUMIA Logo](https://numia.ir/static/images/logo_numia.png)

[![Website](https://img.shields.io/badge/Website-numia.ir-blue)](https://numia.ir)
[![License](https://img.shields.io/badge/License-Proprietary-red)](#license--copyright)
[![Persian](https://img.shields.io/badge/فارسی-README-green)](#نسخه-فارسی)

**[🇬🇧 English](#english-version) | [🇮🇷 فارسی](#نسخه-فارسی)**

</div>

---

## English Version

### Overview

**NUMIA** is an intelligent, native, and comprehensive platform for **real-time monitoring of network uploads** and advanced cybersecurity management. Focused on detecting suspicious activities, preventing data leaks, and providing full control over data flows, NUMIA enables organizations to identify, log, and neutralize internal and external threats instantly.

Fully designed and developed from concept to deployment by **Mohammad Hossein Soleimani**, NUMIA is a scalable, operational, and user-friendly solution available at **[numia.ir](https://numia.ir)**.

> **NUMIA is the first Iranian platform to integrate network monitoring, data protection, USB control, and centralized management into a unified ecosystem.**

---

### What NUMIA Does

NUMIA uses **lightweight, intelligent agents** installed on user devices to monitor network activity at the packet level. It includes **three dedicated agents** for different operating systems:

#### Dedicated Client Agents
| OS          | Status     | Key Features |
|-------------|------------|--------------|
| **Windows** | ✅ Operational | Full USB monitoring, registry management, Write Protection, remote command execution |
| **Linux**   | ✅ Operational | Stable daemon, system logging, secure server communication |
| **macOS**   | ✅ Operational | macOS Security Model compatibility, daemon management, advanced monitoring |

#### Core System Capabilities

**Network Monitoring & Analytics**
- Precise upload volume tracking in **10-second** and **60-second** intervals
- Detection of abnormal data transfer patterns
- Real-time reporting of **CPU** and **RAM** usage
- **Heartbeat system** for device online status verification

**USB Control & Protection**
- Monitoring of all files copied to USB drives
- **Write Protection** with automatic deletion of unauthorized files
- **Full USB port lockdown** remotely
- Detailed logs including device name, file path, and size

**Security & Encryption**
- End-to-End encryption using **AES-256** and **HMAC** validation
- Secure server communication via **HTTPS** with dedicated keys
- Secure storage of credentials in system-persistent paths

**Centralized & Intelligent Management**
- Remote command execution
- Windows registry management (Windows client)
- Web dashboard with advanced analytics and graphical reports
- Support for up to **500 devices** in SaaS model

**Support & Communication**
- Integrated ticketing system with Open/In-Progress/Resolved statuses
- Notifications via **email** and **SMS**
- 24/7 support in SaaS model

**Multilingual & User-Friendly**
- Fully **multilingual interface**: Persian, English, Russian, Turkish
- Automatic **RTL/LTR** support
- Responsive design optimized for mobile and desktop

---

### Technologies Used

NUMIA is built with a modern, secure, and scalable tech stack primarily powered by **Python 3**:

- **Backend & Core Logic**: Python 3.x (FastAPI for API, Celery for async tasks, SQLAlchemy ORM)
- **Database**: PostgreSQL with analytics extensions
- **Frontend**: HTML/CSS/JavaScript with Bootstrap and Chart.js for dashboards
- **Client Agents**: Python-based cross-platform agents (using `psutil`, `pyusb`, `scapy` for packet capture)
- **Encryption & Security**: Cryptography library (AES-256, HMAC), HTTPS/TLS
- **Deployment**: Docker, Kubernetes-ready; supports cloud and on-premise
- **Infrastructure**: Redis for caching, RabbitMQ for queuing, Nginx as reverse proxy

The entire system emphasizes performance, low resource usage, and native integration without unnecessary third-party dependencies.

---

### Competitive Advantages

With its native design and focus on real-world needs in the Iranian market, NUMIA offers unique competitive edges:

| Advantage | Description |
|---------|-----------|
| **Fully Localized** | Built for Iranian regulations, culture, and infrastructure |
| **Competitive Pricing** | 60–70% cheaper than foreign solutions like Cisco Umbrella or Zscaler |
| **Sanction-Proof** | No access, support, or update restrictions |
| **Dual Deployment Models** | SaaS (cloud) and On-Premise (local) with full flexibility |
| **High Scalability** | Up to 500 devices in SaaS, unlimited in On-Premise |
| **Persian Support** | Fast, local-timezone response and assistance |
| **Three Dedicated Agents** | Full coverage for Windows, Linux, and macOS without third-party tools |
| **Native Security** | Internal encryption, no reliance on external services |

---

### Business Models

NUMIA offers two flexible business models tailored to all organization sizes:

#### 1. SaaS Model (Subscription)
- Hosted on **[numia.ir](https://numia.ir)**
- Automatic updates
- 24/7 support
- Up to **500 devices** per organization
- **10-day free trial** with full access to all features

#### 2. On-Premise Model (Local Installation)
- Deployed on your internal infrastructure
- Complete data sovereignty
- No device limits
- Advanced customization capabilities
- Ideal for security-sensitive organizations

---

### Get Started

**Start with a 10-day free trial!**  
Simply register at **[numia.ir](https://numia.ir)** and get instant access to all platform features — no demo or approval needed.

---

### Contact

For more information, collaboration, or customization:

📧 **Email:** [info@numia.ir](mailto:info@numia.ir)  
🌐 **Website:** [numia.ir](https://numia.ir)  
👨‍💻 **Developer & Project Lead:** Mohammad Hossein Soleimani  
🏢 **Company:** Vira Afzar Taraz  

---

> **NUMIA — Intelligent Monitoring, Enduring Security.**  
> *Your data protection is our priority.*

---
---

## نسخه فارسی

### معرفی

**NUMIA** یک پلتفرم هوشمند، بومی و جامع برای **نظارت Real-Time بر آپلودهای شبکه** و مدیریت پیشرفته امنیت سایبری است. این سیستم با تمرکز بر شناسایی فعالیت‌های مشکوک، جلوگیری از نشت داده و ارائه کنترل کامل بر جریان اطلاعات، به سازمان‌ها کمک می‌کند تا تهدیدات داخلی و خارجی را به‌صورت لحظه‌ای شناسایی، ثبت و خنثی کنند.

NUMIA از ایده‌پردازی تا پیاده‌سازی کامل توسط **محمد حسین سلیمانی** توسعه یافته و به‌عنوان یک راه‌حل عملیاتی، مقیاس‌پذیر و کاربرپسند، در دامنه رسمی **[numia.ir](https://numia.ir)** در دسترس است.

> **NUMIA اولین پلتفرم ایرانی است که نظارت شبکه، حفاظت داده، کنترل USB و مدیریت مرکزی را در یک اکوسیستم یکپارچه ارائه می‌دهد.**

---

### کارکرد NUMIA

NUMIA با استفاده از **ایجنت‌های هوشمند و سبک** که روی دستگاه‌های کاربران نصب می‌شوند، فعالیت‌های شبکه را در سطح پایین (Packet-level) رصد می‌کند. این سیستم شامل سه ایجنت اختصاصی برای سیستم‌عامل‌های مختلف است:

#### ایجنت‌های اختصاصی
| سیستم‌عامل | وضعیت | ویژگی‌های کلیدی |
|-------------|--------|-------------------|
| **Windows** | ✅ عملیاتی | نظارت کامل USB، رجیستری، Write Protection، Command Execution |
| **Linux**   | ✅ عملیاتی | Daemon پایدار، لاگ‌گیری سیستمی، ارتباط امن با سرور |
| **macOS**   | ✅ عملیاتی | سازگاری با macOS Security Model، مدیریت Daemon، نظارت پیشرفته |

#### قابلیت‌های اصلی سیستم

**نظارت و تحلیل شبکه**
- ثبت دقیق حجم آپلود در بازه‌های **۱۰ ثانیه** و **۶۰ ثانیه**
- شناسایی الگوهای غیرعادی انتقال داده
- گزارش‌گیری لحظه‌ای از مصرف **CPU** و **RAM**
- سیستم **Heartbeat** برای تأیید وضعیت آنلاین دستگاه‌ها

**کنترل و حفاظت USB**
- نظارت بر تمام فایل‌های کپی‌شده به درایوهای USB
- **حفاظت از نوشتن (Write Protection)** با حذف خودکار فایل‌های غیرمجاز
- **قفل کامل پورت USB** از راه دور
- ثبت لاگ دقیق شامل نام دستگاه، مسیر فایل و حجم

**امنیت و رمزنگاری**
- رمزنگاری End-to-End با **AES-256** و اعتبارسنجی **HMAC**
- ارتباط امن با سرور از طریق **HTTPS** و کلیدهای اختصاصی
- ذخیره‌سازی امن اطلاعات در مسیرهای پایدار سیستم

**مدیریت مرکزی و هوشمند**
- اجرای دستورات از راه دور (Remote Command Execution)
- مدیریت رجیستری ویندوز (ویژه کلاینت ویندوز)
- داشبورد وب با آنالیتیکس پیشرفته و گزارش‌های گرافیکی
- مدیریت دستگاه‌ها تا **۵۰۰ دستگاه** در مدل SaaS

**پشتیبانی و ارتباط**
- سیستم تیکتینگ یکپارچه با وضعیت‌های باز/در حال بررسی/حل‌شده
- ارسال نوتیفیکیشن از طریق **ایمیل** و **SMS**
- پشتیبانی ۲۴/۷ در مدل SaaS

**چندزبانه و کاربرپسند**
- رابط کاربری کاملاً **چندزبانه**: فارسی، انگلیسی، روسی، ترکی
- پشتیبانی از **RTL/LTR** خودکار
- طراحی ریسپانسیو و بهینه برای موبایل و دسکتاپ

---

### تکنولوژی‌های استفاده شده

NUMIA با یک پشته فناوری مدرن، امن و مقیاس‌پذیر که عمدتاً بر پایه **Python 3** است، توسعه یافته:

- **بک‌اند و منطق اصلی**: Python 3.x (FastAPI برای API، Celery برای تسک‌های async، SQLAlchemy ORM)
- **پایگاه داده**: PostgreSQL با افزونه‌های آنالیتیکس
- **فرانت‌اند**: HTML/CSS/JavaScript با Bootstrap و Chart.js برای داشبوردها
- **ایجنت‌های کلاینت**: ایجنت‌های مبتنی بر Python (با استفاده از `psutil`، `pyusb`، `scapy` برای packet capture)
- **رمزنگاری و امنیت**: کتابخانه Cryptography (AES-256، HMAC)، HTTPS/TLS
- **استقرار**: Docker، آماده Kubernetes؛ پشتیبانی از cloud و on-premise
- **زیرساخت**: Redis برای caching، RabbitMQ برای queuing، Nginx به عنوان reverse proxy

کل سیستم بر عملکرد، مصرف پایین منابع و یکپارچگی بومی بدون وابستگی‌های غیرضروری تأکید دارد.

---

### مزیت‌های رقابتی

NUMIA با طراحی بومی و تمرکز بر نیازهای واقعی بازار ایران، مزیت‌های رقابتی منحصربه‌فردی دارد:

| مزیت | توضیح |
|------|-------|
| **بومی‌سازی کامل** | طراحی شده برای قوانین، فرهنگ و زیرساخت‌های ایران |
| **قیمت رقابتی** | ۶۰-۷۰٪ ارزان‌تر از راه‌حل‌های خارجی مانند Cisco Umbrella یا Zscaler |
| **عدم وابستگی به تحریم** | بدون محدودیت دسترسی، پشتیبانی یا به‌روزرسانی |
| **دو مدل استقرار** | SaaS (ابری) و On-Premise (محلی) با انعطاف‌پذیری کامل |
| **مقیاس‌پذیری بالا** | تا ۵۰۰ دستگاه در SaaS، نامحدود در On-Premise |
| **پشتیبانی فارسی** | پاسخگویی سریع و در ساعات کاری ایران |
| **سه ایجنت اختصاصی** | پوشش کامل Windows، Linux و macOS بدون ابزار ثالث |
| **امنیت بومی** | رمزنگاری داخلی، بدون وابستگی به سرویس‌های خارجی |

---

### مدل‌های کسب‌وکار

NUMIA دو مدل تجاری انعطاف‌پذیر برای انواع سازمان‌ها ارائه می‌دهد:

#### ۱. مدل SaaS (اشتراکی)
- میزبانی ابری در **[numia.ir](https://numia.ir)**
- به‌روزرسانی خودکار
- پشتیبانی ۲۴/۷
- حداکثر **۵۰۰ دستگاه** به ازای هر سازمان
- **آزمایش رایگان ۱۰ روزه** با دسترسی کامل به تمام قابلیت‌ها

#### ۲. مدل On-Premise (نصب محلی)
- نصب در زیرساخت داخلی سازمان
- استقلال کامل داده‌ها
- بدون محدودیت تعداد دستگاه
- قابلیت سفارشی‌سازی پیشرفته
- مناسب برای سازمان‌های حساس به امنیت

---

### شروع کنید

**با ۱۰ روز استفاده رایگان شروع کنید!**  
فقط کافیست در **[numia.ir](https://numia.ir)** ثبت‌نام کنید و بلافاصله به تمام قابلیت‌های پلتفرم دسترسی پیدا کنید — بدون نیاز به دمو یا تأیید دستی.

---

### تماس با ما

برای اطلاعات بیشتر، همکاری یا سفارشی‌سازی:

📧 **ایمیل:** [info@numia.ir](mailto:info@numia.ir)  
🌐 **وبسایت:** [numia.ir](https://numia.ir)  
👨‍💻 **توسعه‌دهنده و مدیر پروژه:** محمد حسین سلیمانی  
🏢 **شرکت:** ویرا افزار تاراز  

---

> **NUMIA — نظارت هوشمند، امنیت پایدار.**  
> *حفاظت از داده‌های شما، اولویت ماست.*

---

## License & Copyright

### Proprietary License - All Rights Reserved

**© 2025 Mohammad Hossein Soleimani & Vira Afzar Taraz Company. All Rights Reserved.**

---

### **TERMS OF USE**

This repository and all associated materials (including but not limited to documentation, images, logos, design assets, and any descriptive content) are the **exclusive intellectual property** of:

**Mohammad Hossein Soleimani**  
CEO & Lead Developer  
**Vira Afzar Taraz Company**  
🌐 Website: [codingtaraz.com](https://codingtaraz.com)  
👤 Personal: [mhsoleymani.ir](https://mhsoleymani.ir)

---

### **PROHIBITED ACTIONS**

The following actions are **strictly prohibited** without explicit written authorization:

❌ **Commercial Use:** Using any part of this project for commercial purposes  
❌ **Reproduction:** Copying, duplicating, or reproducing any content  
❌ **Distribution:** Sharing, publishing, or distributing this material  
❌ **Modification:** Altering, adapting, or creating derivative works  
❌ **Reverse Engineering:** Attempting to extract, decompile, or reverse-engineer any component  
❌ **Trademark Infringement:** Using the NUMIA name, logo, or branding without permission  
❌ **Plagiarism:** Claiming this work as your own or removing attribution  

---

### **LEGAL ENFORCEMENT**

**Violations of this license will result in:**

1. **Immediate DMCA Takedown Notice** via GitHub  
2. **Legal action** under Iranian copyright law (قانون حمایت از حقوق مؤلفان و مصنفان - 1348)  
3. **International copyright claims** under Berne Convention provisions  
4. **Financial damages** for commercial exploitation  
5. **Criminal prosecution** where applicable  

We actively monitor for unauthorized use and enforce our rights vigorously.

---

### **PERMITTED USE**

This repository is provided for **informational and showcase purposes only**. You may:

✅ View this repository for educational reference  
✅ Link to this repository with proper attribution  
✅ Mention this project in academic or professional contexts with citation  

---

### **SOURCE CODE ACCESS**

🔒 **The complete source code is NOT publicly available.**

For legitimate inquiries regarding:
- Enterprise licensing  
- White-label partnerships  
- Custom development  
- Technical collaboration  

**Contact us:**  
📧 Email: [info@numia.ir](mailto:info@numia.ir)  
🌐 Official Website: [numia.ir](https://numia.ir)  
🏢 Corporate: [codingtaraz.com](https://codingtaraz.com)

---

### **DISCLAIMER**

This repository serves solely as a **public portfolio showcase**. Any attempt to misuse, replicate, or commercialize this work without authorization will be pursued to the fullest extent of the law.

**By accessing this repository, you acknowledge and agree to these terms.**

---

**NUMIA™ is a registered trademark of Vira Afzar Taraz Company.**  
**Unauthorized use is prohibited and legally actionable.**
