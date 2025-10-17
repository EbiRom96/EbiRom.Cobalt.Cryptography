# Cobalt Cryptography Library / کتابخانه رمزنگاری کبالت

<div dir="rtl">

یک کتابخانه قدرتمند و امن برای رمزنگاری و رمزگشایی با استانداردهای AES256 و AES128

</div>

![.NET Version](https://img.shields.io/badge/.NET%20Standard-2.0-blue)
![.NET Version](https://img.shields.io/badge/.NET-6.0-purple)
![.NET Version](https://img.shields.io/badge/.NET-8.0-green)
![License](https://img.shields.io/badge/License-MIT-yellow)
![NuGet Version](https://img.shields.io/nuget/v/Cobalt.Cryptography)

## 📖 فهرست مطالب / Table of Contents
- [مقدمه فارسی](#مقدمه-فارسی)
- [English Introduction](#english-introduction)
- [ویژگی‌ها / Features](#ویژگیها--features)
- [نصب و راه‌اندازی / Installation](#نصب-و-راهاندازی--installation)
- [راهنمای استفاده / Usage Guide](#راهنمای-استفاده--usage-guide)
- [API Documentation](#api-documentation)
- [نمونه کد / Examples](#نمونه-کد--examples)
- [امنیت / Security](#امنیت--security)
- [مزایا / Benefits](#مزایا--benefits)
- [پشتیبانی از پلتفرم‌ها / Platform Support](#پشتیبانی-از-پلتفرمها--platform-support)
- [توسعه‌دهندگان / Developers](#توسعهدهندگان--developers)
- [مجوز / License](#مجوز--license)

## 🌐 مقدمه فارسی

<div dir="rtl">

### کتابخانه رمزنگاری کبالت

**Cobalt Cryptography Library** یک کتابخانه حرفه‌ای و کاملاً امن برای عملیات رمزنگاری و رمزگشایی در پلتفرم .NET می‌باشد. این کتابخانه با بهره‌گیری از آخرین استانداردهای صنعتی و الگوریتم‌های رمزنگاری پیشرفته، راه‌حلی مطمئن برای حفاظت از داده‌های حساس ارائه می‌دهد.

### 🎯 هدف پروژه
ایجاد یک کتابخانه ساده اما قدرتمند برای توسعه‌دهندگان ایرانی و بین‌المللی که نیاز به انجام عملیات رمزنگاری امن با استانداردهای AES دارند.

### 💡 چرا کبالت؟
- **سادگی در استفاده**: با تنها دو تابع اصلی نیازهای شما را برطرف می‌کند
- **امنیت بالا**: پیاده‌سازی مطابق با بهترین استانداردهای امنیتی
- **چندپلتفرمی**: اجرا روی تمام پلتفرم‌های .NET
- **مستندات کامل**: راهنمای فارسی و انگلیسی جامع

</div>

## 🌍 English Introduction

### Cobalt Cryptography Library

**Cobalt Cryptography Library** is a professional and highly secure library for encryption and decryption operations on the .NET platform. Leveraging the latest industry standards and advanced encryption algorithms, it provides a reliable solution for protecting sensitive data.

### 🎯 Project Goal
To create a simple yet powerful library for Iranian and international developers who need to perform secure encryption operations with AES standards.

### 💡 Why Cobalt?
- **Easy to Use**: Meets your needs with just two main functions
- **High Security**: Implementation following the best security standards
- **Cross-Platform**: Runs on all .NET platforms
- **Comprehensive Documentation**: Complete Persian and English guides

## ✨ ویژگی‌ها / Features

<div dir="rtl">

### ویژگی‌های اصلی
- ✅ **رمزنگاری AES256** با پشتیبانی از Salt
- ✅ **رمزنگاری AES128** با پشتیبانی از Salt
- ✅ **استفاده از PBKDF2** با ۱۰۰۰۰ تکرار برای استخراج کلید
- ✅ **تولید خودکار Salt** و IV برای هر عملیات
- ✅ **پشتیبانی از استانداردهای امنیتی** صنعتی
- ✅ **خطایابی جامع** و مدیریت خطاهای مناسب

### ویژگی‌های فنی
- 🔒 الگوریتم SHA256 برای استخراج کلید
- 🛡️ حالت CBC برای رمزنگاری
- 📦 Padding نوع PKCS7
- 🎯 سازگاری کامل با استانداردهای AES

</div>

### Key Features
- ✅ **AES256 Encryption** with Salt support
- ✅ **AES128 Encryption** with Salt support
- ✅ **PBKDF2 usage** with 10,000 iterations for key derivation
- ✅ **Automatic Salt and IV generation** for each operation
- ✅ **Industrial security standards** compliance
- ✅ **Comprehensive error handling** and proper error management

### Technical Features
- 🔒 SHA256 algorithm for key derivation
- 🛡️ CBC mode for encryption
- 📦 PKCS7 padding type
- 🎯 Full compatibility with AES standards

## 🚀 نصب و راه‌اندازی / Installation

<div dir="rtl">

### از طریق NuGet

```bash
dotnet add package Cobalt.Cryptography