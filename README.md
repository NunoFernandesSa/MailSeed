# 🌐 MailSeed — Map the Usage of Your Email Addresses

[![AdonisJS](https://img.shields.io/badge/Framework-AdonisJS%20v6-5a45ff?style=flat-square&logo=adonisjs)](https://adonisjs.com/)
[![Tailwind CSS](https://img.shields.io/badge/CSS-Tailwind%20v4-38bdf8?style=flat-square&logo=tailwindcss)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Bundler-Vite-646cff?style=flat-square&logo=vite)](https://vite.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

> **MailSeed** (formerly _MailMap_) is a full-stack web application designed to **centralize**, **organize**, and **map** the usage of all your email addresses.

Whether you have multiple personal, professional, academic, or sign-up email accounts, MailSeed helps you instantly find **which email address is linked to which online service**.

---

## 📖 Table of Contents

- [🎯 Project Overview](#-project-overview)
- [🚀 Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [📂 Architecture](#-architecture)
- [⚙️ Installation](#️-installation)
- [🚀 Running the Project](#-running-the-project)
- [📌 Roadmap](#-roadmap)
- [💡 Use Cases](#-use-cases)
- [👤 Author](#-author)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

# 🎯 Project Overview

Nowadays, most of us own multiple email addresses:

- 📧 Personal email
- 💼 Work email
- 🛒 Shopping email
- 📨 Junk mail address
- 🎓 Student email
- 🔐 Email reserved for sensitive accounts

After a few years, it becomes almost impossible to remember:

- Which email did I use for Netflix?
- Which address is linked to my Kraken account?
- Which account is associated with LinkedIn?
- Which email did I use to create my GitHub account?
- Which address should I use to reset my password?

**MailSeed** solves exactly this problem.

The application acts as a true **map of your digital identity**, linking each of your email addresses to the platforms where they are used.

---

# 🚀 Features

## 📧 Email Address Management

- Add multiple email addresses
- Organize them easily
- Edit or delete them
- Instantly identify where each one is used

---

## 🗂️ Platform Management

Associate each email address with platforms such as:

- Netflix
- Amazon
- GitHub
- LinkedIn
- Kraken
- Revolut
- Google
- Discord
- Steam
- Spotify
- and many more.

Each platform is linked to **a single email address**, making it easy to retrieve the correct account whenever you need it.

---

## 🔍 Instant Search

Search by:

- Platform name
- Email address
- Keyword

And instantly find the matching association.

---

## 📊 Dashboard

A modern interface that lets you visualize:

- All your email addresses
- All associated services
- The number of platforms linked to each email
- A clean, card-based navigation experience

---

## 🔐 Secure Management

The project is designed to run within a secure user workspace.

Future versions will include:

- User authentication
- Data encryption
- Multi-user support

---

# 🛠️ Tech Stack

The project is built with modern technologies.

| Technology              | Description                             |
| ----------------------- | --------------------------------------- |
| **AdonisJS v6**         | Node.js Backend Framework               |
| **TypeScript**          | Strong typing                           |
| **EdgeJS**              | Template engine                         |
| **Tailwind CSS v4**     | Modern UI framework                     |
| **Vite**                | Lightning-fast bundler                  |
| **Node.js**             | JavaScript runtime                      |
| **SQLite / PostgreSQL** | Database (depending on the environment) |

---

# 📂 Architecture

```text
mailseed/
│
├── app/
│   ├── Controllers/
│   ├── Models/
│   ├── Middleware/
│   ├── Services/
│   └── Validators/
│
├── config/
├── database/
├── resources/
│   ├── views/
│   ├── css/
│   └── js/
│
├── start/
├── public/
├── tests/
│
├── .env
├── package.json
└── README.md
```

---

# ⚙️ Installation

## 1. Clone the repository

```bash
git clone https://github.com/your-account/mailseed.git
```

```bash
cd mailseed
```

---

## 2. Install dependencies

```bash
npm install
```

---

## 3. Configure the environment

```bash
cp .env.example .env
```

Then configure your database settings in the `.env` file.

---

## 4. Run the migrations

```bash
node ace migration:run
```

---

## 5. Start the development server

```bash
node ace serve --watch
```

The application will be available at:

```
http://localhost:3333
```

---

# 🚀 Useful Commands

### Development server

```bash
node ace serve --watch
```

### Asset compilation

```bash
npm run dev
```

### Production build

```bash
npm run build
```

### Run migrations

```bash
node ace migration:run
```

### Reset the database

```bash
node ace migration:refresh
```

---

# 📌 Roadmap

## Version 1

- [x] Email management
- [x] Platform management
- [x] Dashboard
- [x] Quick search

---

## Version 2

- [ ] Authentication
- [ ] User accounts
- [ ] Categories
- [ ] Automatic platform icons
- [ ] Statistics

---

## Version 3

- [ ] CSV import
- [ ] CSV export
- [ ] Cloud synchronization
- [ ] REST API
- [ ] Mobile application

---

# 💡 Use Cases

MailSeed is especially useful if you:

- manage multiple email addresses;
- use dozens or even hundreds of online services;
- regularly forget which email is linked to a specific account;
- want to better organize your digital identity;
- are looking for a simple dashboard to manage your online accounts.

---

# 👤 Author

Developed with ❤️ by **Nuno Fernandes**

**Full-Stack Engineer**

If you'd like to discuss the project, suggest improvements, or collaborate, feel free to get in touch.

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch:

```bash
git checkout -b feature/my-feature
```

3. Commit your changes:

```bash
git commit -m "Add my new feature"
```

4. Push your branch:

```bash
git push origin feature/my-feature
```

5. Open a Pull Request.

---

# 📄 License

This project is distributed under the **MIT License**.

You are free to:

- use the project;
- modify it;
- distribute it;
- adapt it to your needs.

See the **LICENSE** file for more information.

---

**MailSeed** 🌱

_Map your digital identity, one email address at a time._
