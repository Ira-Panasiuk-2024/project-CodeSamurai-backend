# Money Guard - Backend API

---

### 🇺🇸 English

## 📋 About the Project

**Money Guard** is a full-stack personal finance management application developed by the CodeSamurai team. This repository contains the server-side part of the project, providing API for managing transactions, categories, and financial analytics.

## 🎯 Key Features

- 🔐 User authentication and authorization
- 👤 User profile management with avatars (Cloudinary)
- 💰 Financial transaction management (income/expenses)
- 📊 Operation categorization
- 📈 Expense statistics and analytics
- 🔒 Secure data storage
- 📱 RESTful API for frontend application

## 🛠 Technologies

- **Runtime:** Node.js
- **Framework:** Express.js
- **Database:** MongoDB with Mongoose ODM
- **Authentication:** JWT (JSON Web Tokens)
- **Validation:** Joi
- **API Documentation:** Swagger
- **Middleware:** CORS
- **Password Hashing:** bcrypt
- **Image Storage:** Cloudinary

## 🚀 Installation and Setup

### Prerequisites

- Node.js (version 18 or higher)
- MongoDB
- npm or yarn

### Installation Steps

1. **Clone the repository:**

```bash
git clone https://github.com/Ira-Panasiuk-2024/project-CodeSamurai-backend.git
cd project-CodeSamurai-backend
```

2. **Install dependencies:**

```bash
npm install
```

3. **Set up environment variables:**
   Create a `.env` file in the root directory:

```env
PORT=3000
MONGODB_USER=
MONGODB_PASSWORD=
MONGODB_URL=
MONGODB_DB=

JWT_SECRET=
APP_DOMAIN=

CLOUD_NAME=
API_KEY=
API_SECRET=

ENABLE_CLOUDINARY=
```

4. **Start the server:**

For development:

```bash
npm run dev
```

For production:

```bash
npm start
```

## 📚 API Documentation

API documentation is available at: `http://localhost:3000/api-docs` (after starting the server)

### Main Endpoints:

- `POST /auth/register` - User registration
- `POST /auth/login` - User login
- `POST /auth/logout` - User logout
- `GET /users/current` - Get current user
- `PATCH /users/current` - Update user avatar
- `GET /transactions` - Get transactions
- `POST /transactions` - Create transaction
- `DELETE /transactions/:id` - Delete transaction
- `PATCH /transactions/:id` - Update transaction
- `GET /categories` - Get categories
- `GET /transactions/statistics` - Transaction statistics

## 👥 Development Team

**CodeSamurai Team:**

- **Ira Panasiuk** - Backend Developer & Scrum Master

- [Other team members]

**My Responsibilities:**

- RESTful API development (users, transactions, categories, statistics)

- Team coordination as Scrum Master

## 🔗 Related Projects

- **Frontend:** [Money Guard Frontend](https://github.com/Ira-Panasiuk-2024/project-CodeSamurai-frontend)

- **Live Demo:** [https://project-code-samurai-frontend.vercel.app/](https://project-code-samurai-frontend.vercel.app/)

## 📄 License

This project was created for educational purposes.

---

### 🇺🇦 Українська

## 📋 Про проєкт

**Money Guard** - це фулстек додаток для управління особистими фінансами, розроблений командою CodeSamurai. Цей репозиторій містить серверну частину проєкту, яка забезпечує API для управління транзакціями, категоріями та аналітикою фінансових операцій.

## 🎯 Основні функції

- 🔐 Автентифікація та авторизація користувачів
- 👤 Управління профілями користувачів з аватарами (Cloudinary)
- 💰 Управління фінансовими транзакціями (доходи/витрати)
- 📊 Категоризація операцій
- 📈 Статистика та аналітика витрат
- 🔒 Безпечне зберігання даних
- 📱 RESTful API для фронтенд додатку

## 🛠 Технології

- **Runtime:** Node.js
- **Framework:** Express.js
- **База даних:** MongoDB з Mongoose ODM
- **Автентифікація:** JWT (JSON Web Tokens)
- **Валідація:** Joi
- **Документація API:** Swagger
- **Middleware:** CORS
- **Хешування паролів:** bcrypt
- **Зберігання зображень:** Cloudinary

## 🚀 Встановлення та запуск

### Передумови

- Node.js (версія 18 або вище)
- MongoDB
- npm або yarn

### Кроки встановлення

1. **Клонування репозиторію:**

```bash
git clone https://github.com/Ira-Panasiuk-2024/project-CodeSamurai-backend.git
cd project-CodeSamurai-backend
```

2. **Встановлення залежностей:**

```bash
npm install
```

3. **Налаштування змінних середовища:**
   Створіть файл `.env` у кореневій папці:

```env
PORT=3000
MONGODB_USER=
MONGODB_PASSWORD=
MONGODB_URL=
MONGODB_DB=

JWT_SECRET=
APP_DOMAIN=

CLOUD_NAME=
API_KEY=
API_SECRET=

ENABLE_CLOUDINARY=
```

4. **Запуск сервера:**

Для розробки:

```bash
npm run dev
```

Для продакшену:

```bash
npm start
```

## 📚 API Документація

API документація доступна за адресою: `http://localhost:3000/api-docs` (після запуску сервера)

### Основні ендпоінти:

- `POST /auth/register` - Реєстрація користувача
- `POST /auth/login` - Вхід користувача
- `POST /auth/logout` - Вихід користувача
- `GET /users/current` - Отримання поточного користувача
- `PATCH /users/current` - Оновлення аватара користувача
- `GET /transactions` - Отримання транзакцій
- `POST /transactions` - Створення транзакції
- `DELETE /transactions/:id` - Видалення транзакції
- `PATCH /transactions/:id` - Оновлення транзакції
- `GET /categories` - Отримання категорій
- `GET /transactions/statistics` - Статистика транзакцій

## 👥 Команда розробки

**Команда CodeSamurai:**

- **Ірина Панасюк** - Бекенд розробник та скрам-мастер

- [Інші учасники команди]

**Мої обов'язки:**

- Створення RESTful API (користувачі, транзакції, категорії, статистика)

- Координація роботи команди як Scrum Master

## 🔗 Пов'язані проєкти

- **Фронтенд код:** [Money Guard Frontend](https://github.com/Ira-Panasiuk-2024/project-CodeSamurai-frontend)

- **Фронтенд жива сторінка:** [https://project-code-samurai-frontend.vercel.app/](https://project-code-samurai-frontend.vercel.app/)

## 📄 Ліцензія

Цей проєкт створено у навчальних цілях.
