
# 🛒 MarketSphere

**MarketSphere** is a modern e-commerce platform built with **React**, **TypeScript**, **Node.js**, and **MySQL**.  
It provides a scalable full-stack architecture for product listing, user management, and future shopping features.

---

## 📦 Tech Stack

| Frontend  | Backend         | Database | Language   |
|-----------|------------------|----------|------------|
| React     | Express (Node.js) | MySQL    | TypeScript |

---

## 📁 Project Structure

```
market-sphere/
├── client/         # Frontend (React + TypeScript)
│   ├── src/
│   └── public/
├── server/         # Backend (Express + TypeScript)
│   ├── src/
│   └── .env
├── .gitignore
├── README.md
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/market-sphere.git
cd market-sphere
```

### 2. Install Frontend

```bash
cd client
npm install
npm start
```

### 3. Install Backend

```bash
cd ../server
npm install
npm run dev
```

---

## 🔐 Environment Variables

Create a `.env` file in `/server`:

```env
PORT=5000
DB_HOST=localhost
DB_USER=your_username
DB_PASSWORD=your_password
DB_NAME=market_db
```

---

## 📌 Features (Planned)

- [x] Frontend/Backend project setup
- [ ] RESTful API for Products
- [ ] MySQL integration
- [ ] User authentication (JWT)
- [ ] Admin dashboard

---

## 📄 License

This project is licensed under the MIT License.
