# Frappe Bench Project

Welcome to the **Frappe Bench** project! This repository contains the source code and configuration for your Frappe/ERPNext development environment.

---

## 🚀 Overview

Frappe Bench is a command-line tool to manage Frappe/ERPNext applications and sites. It helps you set up, develop, and maintain your ERPNext projects efficiently.

---

## 📦 Features

- Easy setup and management of Frappe/ERPNext sites
- Automated environment configuration
- App installation and updates
- Backup and restore utilities

---

## 🛠️ Getting Started

### Prerequisites

- Python 3.6+
- Node.js & npm
- Redis, MariaDB/MySQL, Yarn
- wkhtmltopdf (for PDF generation)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/frappe-bench.git
   cd frappe-bench
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Initialize bench:**
   ```bash
   bench init my-bench
   cd my-bench
   ```

4. **Create a new site:**
   ```bash
   bench new-site your-site-name
   ```

5. **Get ERPNext app:**
   ```bash
   bench get-app erpnext
   bench --site your-site-name install-app erpnext
   ```

6. **Start the server:**
   ```bash
   bench start
   ```

---

## 📚 Documentation

- [Frappe Framework Docs](https://frappeframework.com/docs)
- [ERPNext Docs](https://docs.erpnext.com/)

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request

---

## 📝 License

This project is licensed under the MIT License.

---

## 📬 Contact

For questions or support, please open an issue or contact [your.email@example.com](mailto:your.email@example.com).

---
