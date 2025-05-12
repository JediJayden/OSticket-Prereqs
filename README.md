# 🛠️ osTicket Installation Project

This project documents the step-by-step installation and configuration of the osTicket support ticket system in a Windows Server lab environment.

## 📌 Project Overview

osTicket is an open-source helpdesk solution. This lab showcases my ability to configure and deploy an enterprise-level IT support system using Windows Server, IIS, PHP, and MySQL.

---

## 🔧 Technologies Used

- Windows Server 2019
- osTicket
- Internet Information Services (IIS)
- MySQL / PHPMyAdmin
- PHP
- SMTP (Email setup)

---

## 📸 Screenshots

> Include a few screenshots of each major step: IIS setup, osTicket install page, admin dashboard, etc.

---

## 🧭 Installation Steps

### 1. Prerequisites
- Enabled Windows features: IIS, CGI
- Installed PHP 7.x
- Installed MySQL + PHPMyAdmin
- Downloaded osTicket from [official site](https://osticket.com/download/)

### 2. Configure IIS
- Set up new site in IIS pointing to `osTicket` folder
- Verified PHP handler mappings
- Enabled necessary modules

### 3. osTicket Installation
- Accessed installation via `http://localhost/osTicket`
- Configured database and admin credentials

### 4. Post-Install Configuration
- Renamed `config.php`
- Deleted setup directory
- Set permissions for attachments and logs folders

---

## ✅ Outcome

After installation and configuration, osTicket was up and running and ready to handle support tickets efficiently.

---

## 📂 Related Projects

- [Post-Installation Configuration](https://github.com/joshmadakorcc/post-install-config)
- [Ticket Lifecycle Examples](https://github.com/joshmadakorcc/ticket-lifecycle)

---

## 📬 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/jayden-orlandini-4555a71b6)

