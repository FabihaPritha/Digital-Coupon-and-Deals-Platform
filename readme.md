## Digital Coupon and Deals Platform

A web-based platform for local businesses to create, manage, and promote digital coupons and deals. Built with **PHP Laravel on the backend, the system supports Google Email Authentication, **coupon management, **redemption tracking, and integrates with **email marketing and social media APIs to help businesses boost engagement and drive sales.

---

## 🚀 Features

- ✅ Google Login Authentication (OAuth 2.0)
- 🏷 Coupon Management
  - Create/Edit/Delete Coupons
  - Set usage limits, expiration, and categories
- 📊 Redemption Tracking
  - User-wise tracking
  - Real-time status updates
- 📧 Email Marketing Integration
  - (Mailchimp, SendinBlue or custom SMTP)
- 🔐 Role-based Access (Admin, Business Owner, Customer)
- 🔍 Coupon Search & Filter (by location, business, type, etc.)

---

## 🛠 Tech Stack

- Backend: PHP, Laravel
- Database: MySQL
- Frontend: Blade / Vue.js

---

## 📦 Installation

```bash
git clone https://github.com/nishagithub245/Digital-Coupon-and-Deals-Platform.git
cd local-deals-platform
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate