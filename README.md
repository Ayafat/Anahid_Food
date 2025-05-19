# پروژه Laravel

این پروژه توسط **مهدیه ایافت** ایجاد شده است.

## 🛠 پیش‌نیازها

قبل از اجرای پروژه، مطمئن شوید که موارد زیر روی سیستم شما نصب شده‌اند:

- PHP (نسخه 8.0 یا بالاتر)
- Composer
- Laravel
- MySQL یا MariaDB
- Node.js و npm (برای مدیریت فایل‌های فرانت‌اند)
- Git (اختیاری)

## ⚙️ مراحل نصب و اجرا

1. مخزن را کلون کنید:
   git clone https://github.com/your-username/your-project.git

   2.وارد پوشه پروژه شوید:
   cd <نام_پوشه>
   3.پکیج‌های PHP را نصب کنید:

composer install
4.ساخت فایل تنظیمات .env
cp .env.example .env
5.تولید کلید رمزنگاری اپلیکیشن
php artisan key:generate
6.تنظیم اطلاعات دیتابیس در فایل .env
DB_DATABASE=your_db_name
DB_USERNAME=your_db_user
DB_PASSWORD=your_db_password
7.ساخت جداول دیتابیس با اجرای مایگریشن‌ها

php artisan migrate
8.(اختیاری) وارد کردن داده‌های اولیه
php artisan db:seed
9.نصب پکیج‌های فرانت‌اند و اجرای Vite
npm install
npm run dev
10.اجرای پروژه روی سرور محلی
php artisan serve

11.باز کردن مرورگر در آدرس زیر
http://localhost:8000


تکنولوژی‌های استفاده‌شده
Laravel

PHP

MySQL

HTML5

CSS3

Bootstrap 5

JavaScript

Vite

مجوز
این پروژه تحت مجوز MIT منتشر شده است.

توسعه‌دهنده
مهدیه ایافت
📧 ایمیل: mahdiehayafat@gmail.com
