# 📰 News Portal

A sleek, modern, and feature-rich full-stack news platform built to deliver timely headlines, stunning visuals, and accurate weather updates. With a responsive design, easy-to-use admin tools, and interactive features, it’s ideal for media agencies, local newsrooms, and community boards.

## ✨ Features

* **📅 7-Day Weather Forecast**: Automatically updated weekly via OpenWeatherMap API.
* **📰 Dynamic News Management**: Upload articles with headlines, images, and reporter details.
* **📆 Calendar Integration**: Select a date to view all news from that day instantly.
* **🌗 Light/Dark Mode**: Seamless theme switching for better user experience.
* **📢 Advertisement Placement**: Posters displayed after each article for monetization.
* **🔒 Secure Admin Panel**: Password-protected content management.

## 🛠 Tech Stack

* **Frontend**: React.js + Tailwind CSS
* **Backend**: Node.js + Express.js
* **Database**: MongoDB
* **API**: OpenWeatherMap
* **Authentication**: JWT-based security

## 🚀 Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/news-portal.git
   cd news-portal
   ```
2. **Install backend dependencies:**

   ```bash
   cd server
   npm install
   ```
3. **Install frontend dependencies:**

   ```bash
   cd ../client
   npm install
   ```
4. **Setup environment variables** in `.env` (API keys, DB URI, JWT secret).
5. **Run development servers:**

   * Backend: `npm run dev` (inside `server`)
   * Frontend: `npm start` (inside `client`)

## 📂 Folder Structure

```
news-portal/
├─ client/        # React frontend
├─ server/        # Node.js backend
└─ README.md
```

## 📜 License

Licensed under the **MIT License** — free to use, modify, and share.
