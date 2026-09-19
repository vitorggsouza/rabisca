# 🖊️ Rabisca

## ℹ️ About

Rabisca is a simple and intuitive note-taking website, designed to help its users record tasks, ideas, and reminders in a practical and quick way.

---

## 🖥️ Technologies

### 🎨 Front-end

- **HTML and CSS**: define the structure and appearance of each page.

- **JavaScript**: adds interactivity and functionality to the pages.

- **Bootstrap**: speeds up development and facilitates the creation of responsive interfaces.

- **Bootstrap Icons**: provides icons that enhance the website's appearance.

### 🛠️ Development tools

- **npm**: manages JavaScript packages and dependencies.

- **esbuild**: minifies and bundles CSS and JavaScript files.

- **Composer**: manages PHP packages and dependencies.

### ⚙️ Back-end

- **PHP**: processes the application's logic and business rules.

- **Bramus Router**: enables route creation and the use of friendly URLs.

- **PHP dotenv**: loads environment variables from a `.env` file.

- **PHPMailer**: handles email sending.

### 💾 Database

- **MySQL**: stores and manages the application's data.

---

## 🚀 How to run

1. Clone the repository:

```bash
git clone https://github.com/vitorggsouza/rabisca.git
```

2. Access the project folder:

```bash
cd rabisca/
```

3. Install the front-end dependencies:

```bash
npm install
```

4. Install the back-end dependencies:

```bash
composer install
```

5. Run the development script:

```bash
npm run dev
```

6. Or run the production script:

```bash
npm run build
```

---

## 🗂️ Folder structure

```text
rabisca/
├── docs/
│   └── palette.jpeg
├── public/
│   ├── assets/
│   │   ├── favicons/
│   │   │   ├── android-chrome-192x192.png
│   │   │   ├── android-chrome-512x512.png
│   │   │   ├── apple-touch-icon.png
│   │   │   ├── favicon-16x16.png
│   │   │   ├── favicon-32x32.png
│   │   │   └── favicon.svg
│   │   └── img/
│   │       ├── dev.webp
│   │       ├── hero.svg
│   │       └── logo.svg
│   ├── .htaccess
│   ├── favicon.ico
│   ├── index.php
│   └── site.webmanifest
├── src/
│   ├── css/
│   │   ├── base/
│   │   ├── components/
│   │   ├── layouts/
│   │   ├── pages/
│   │   └── app.css
│   ├── js/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── utils/
│   │   └── app.js
│   ├── php/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── helpers/
│   │   ├── models/
│   │   ├── templates/
│   │   └── views/
│   └── sql/
│       └── schema.sql
├── .env.example
├── .gitignore
├── build.js
├── composer.json
├── composer.lock
├── LICENSE
├── package-lock.json
├── package.json
└── README.md
```

---

## 🚦 Status

In development.

---

## 📜 License

This project is licensed under the **MIT License**. For more details, see the LICENSE file.

---

Developed by **Vitor Souza**.