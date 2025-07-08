# API-Postman-Documentation
# 🌍 Youth Opportunities API

A RESTful Laravel API that allows authenticated users to manage and filter **scholarships, training, and job opportunities** by type, region, and status.

---

## 🚀 Features

- User Registration & Authentication (Laravel Sanctum)
- CRUD Operations for Opportunities
- Filter Opportunities by:
  - Type (`Scholarship`, `Job`, `Training`)
  - Region (e.g., `Ghana`, `Nigeria`)
  - Status (`active`, `closed`, `expired`)
- Fully documented API via Postman
- Secure token-based access

---

## 🛠️ Tech Stack

- PHP (Laravel 11+)
- MySQL
- Laravel Sanctum (Authentication)
- Postman (API Testing & Documentation)

---

## 📂 Installation Guide

### Prerequisites
- PHP 8.1+
- Composer
- MySQL
- Laravel CLI

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/k-daks101/youth-opportunities-api.git
cd youth-opportunities-api

# 2. Install dependencies
composer install

# 3. Create .env file
cp .env.example .env

# 4. Generate application key
php artisan key:generate

# 5. Update DB credentials in .env
DB_DATABASE=your_db_name
DB_USERNAME=your_username
DB_PASSWORD=your_password

# 6. Run migrations
php artisan migrate

# 7. Serve the application
php artisan serve

