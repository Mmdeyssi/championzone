# ChampionZone — Sports Community Web App

> A responsive sports community platform with user authentication and dynamic content

![Frontend](https://img.shields.io/badge/Frontend-HTML%20%2F%20CSS%20%2F%20JavaScript-orange?style=flat-square)
![Backend](https://img.shields.io/badge/Backend-PHP%20%2F%20MySQL-777BB4?style=flat-square&logo=php)
![Deploy](https://img.shields.io/badge/Deployed-Vercel-black?style=flat-square&logo=vercel)
![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square)



---

## 🏆 What is ChampionZone?

ChampionZone is a **responsive sports community web application** that brings sports fans together. Users can sign up, log in, and access dynamic sports content — all through a clean, mobile-friendly interface built with HTML, CSS, JavaScript, PHP, and MySQL.

---

## ✨ Features

- 🔐 User registration and login system with PHP authentication
- 🗄️ MySQL database integration for persistent user data
- 📱 Fully responsive design across all screen sizes
- 🎨 Clean, modern UI with custom CSS and web fonts
- 🏅 Dynamic sports content pages


---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, JavaScript |
| Backend | PHP |
| Database | MySQL |
| Auth | PHP session-based authentication |
| Deployment | Vercel |
| Version Control | Git / GitHub |

---

## 📁 Project Structure

```
championzone/
├── assets/          # Images and media files
├── css/             # Stylesheets
├── imgs/            # Image assets
├── js/              # JavaScript files
├── pages/           # HTML page templates
├── webfonts/        # Custom web fonts
├── db_connect.php   # Database connection
├── db_error.php     # Error handling
├── login.html       # Login page
├── login.php        # Login logic
├── signup.html      # Registration page
└── h.html           # Home page
```

---

## 🚀 Getting Started (Local)

### Prerequisites
- PHP 7.4+
- MySQL
- Local server (XAMPP / WAMP / MAMP)

### Installation

```bash
# Clone the repository
git clone https://github.com/Mmdeyssi/championzone.git
cd championzone
```

1. Copy the project into your local server's `htdocs` folder (XAMPP) or `www` folder (WAMP)
2. Create a MySQL database and import the schema
3. Update database credentials in `db_connect.php`:

```php
$host = "localhost";
$user = "root";
$password = "YOUR_PASSWORD";
$database = "championzone";
```

4. Start Apache and MySQL in XAMPP/WAMP
5. Visit `http://localhost/championzone`

---


---

## 👤 Author

**Mouhib Mdaissi**
- 📍 Heidelberg, Germany
- 💼 [linkedin.com/in/mouhib-mdaissi-2262b21ab](https://www.linkedin.com/in/mouhib-mdaissi-2262b21ab)
- 🐙 [github.com/mmdeyssi](https://github.com/mmdeyssi)
