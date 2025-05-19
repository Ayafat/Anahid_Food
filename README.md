# AnahidFood  
این سایت سایتی نمونه ، شبییه به سایت اسنپ فود برای سفارش آنلاین غذا از رستوران هست .


پروژه Laravel
این پروژه توسط مهدیه ایافت ایجاد شده است.

🛠 پیش‌نیازها
قبل از اجرای پروژه، مطمئن شوید که موارد زیر روی سیستم شما نصب شده‌اند:

PHP (نسخه 8.0 یا بالاتر)
Composer
Laravel
MySQL یا MariaDB
Node.js و npm (برای مدیریت فایل‌های فرانت‌اند)
Git (اختیاری)
⚙️ مراحل نصب و اجرا
مخزن را کلون کنید: git clone https://github.com/Ayafat/Anahid_Food.git

2.وارد پوشه پروژه شوید: cd <نام_پوشه> 3.پکیج‌های PHP را نصب کنید:

composer install 4.ساخت فایل تنظیمات .env cp .env.example .env 5.تولید کلید رمزنگاری اپلیکیشن php artisan key:generate 6.تنظیم اطلاعات دیتابیس در فایل .env DB_DATABASE=your_db_name DB_USERNAME=your_db_user DB_PASSWORD=your_db_password 7.ساخت جداول دیتابیس با اجرای مایگریشن‌ها

php artisan migrate 8.(اختیاری) وارد کردن داده‌های اولیه php artisan db:seed 9.نصب پکیج‌های فرانت‌اند و اجرای Vite npm install npm run dev 10.اجرای پروژه روی سرور محلی php artisan serve

11.باز کردن مرورگر در آدرس زیر http://localhost:8000

تکنولوژی‌های استفاده‌شده Laravel

PHP

MySQL

HTML5

CSS3

Bootstrap 5
مجوز این پروژه تحت مجوز MIT منتشر شده است.

توسعه‌دهنده مهدیه ایافت 📧 ایمیل: mahdiehayafat@gmail.com

-------------------------------------------------------------------------------------------------------------------------------------------------------------------# Web Project with Laravel and Bootstrap
This project is a sample food ordering web online application  , designed for placing orders from various restaurants.  

This project was created by **Mahdieh Hayafat**.  
It is built using the **Laravel** framework for the backend, and **HTML, CSS, Bootstrap, and JavaScript** for the frontend.

---
## 🛠 Prerequisites

Make sure the following are installed on your system before running the project:

- PHP 8.0 or higher
- Composer
- Laravel
- MySQL or MariaDB
- Node.js and npm (for asset compilation via Vite)
- Git (optional)

---

## ⚙️ Installation & Setup Steps

### 1. Clone the repository
```bash
git clone https://github.com/your-username/your-project.git
cd your-project





JavaScript

Vite

2. Install PHP dependencies using Composer

composer install
3. Create the .env configuration file

cp .env.example .env

4. Generate the application encryption key
php artisan key:generate

5. Configure your database in .env file

DB_DATABASE=your_db_name
DB_USERNAME=your_db_user
DB_PASSWORD=your_db_password

6. Run database migrations

php artisan migrate

7. (Optional) Seed initial data

php artisan db:seed

8. Install frontend dependencies and build assets using Vite

npm install
npm run dev

9. Serve the application locally
php artisan serve

10. Open the project in your browser:
http://localhost:8000

Technologies Used:

Laravel

PHP

MySQL

HTML5

CSS3

Bootstrap 5

JavaScript

Vite

📄 License
This project is licensed under the MIT License.

📬 Developer
Mahdieh Hayafat
📧 Email: mahdiehayafat@gmail.com



