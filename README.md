<p align="center">
    <a href="https://laravel.com" target="_blank">
        <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
    </a>
</p>

<p align="center">
    <a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
    <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
    <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
    <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

---

# 📬 Laravel Livewire Contact Form

A fully functional contact form built using **Laravel 10** and **Livewire**, featuring:

- Real-time validation
- Queued email notifications
- Third-party API integration
- Admin panel with pagination and search

---

## 🚀 Features

- ✅ Livewire-based contact form
- ✅ Validates and stores data in `contact_submissions` table
- ✅ Dispatches a queued job to email admin
- ✅ Calls third-party API inside the job (`https://jsonplaceholder.typicode.com/posts`)
- ✅ Logs API response in `storage/logs/laravel.log`
- ✅ Bonus: Admin panel to list and search submissions

---

## 📁 Deliverables

- ✅ `.env.example` with configuration placeholders
- ✅ Queueable job with `ShouldQueue` implemented
- ✅ Mailer and third-party API integrated
- ✅ README with setup instructions

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
