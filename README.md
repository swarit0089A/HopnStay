# 🏕️ HopnStay Web Project

Welcome to **HopnStay**, a full-stack web application for exploring and booking stays around the world. This guide will walk you through setting up the project locally.

---

## 📋 Prerequisiteshttps://github.com/swarit0089A

Make sure the following are installed on your system before proceeding:

- [Node.js](https://nodejs.org/) (v18 recommended)
- [MongoDB](https://www.mongodb.com/)
- [Nodemon](https://www.npmjs.com/package/nodemon) (install globally using `npm install -g nodemon`)

---

## ⚙️ Installation Steps

### 1. Clone the Repository

```bash
git clone https://github.com/swarit0089A/Stayquest.git
cd Stayquest
```

---

### 2. Setup Environment Variables

Create a `.env` file in the root directory and add the following:

```env
ATLASDB_URL=mongodb://127.0.0.1:27017/hopnstay
CLOUD_NAME=your_cloud_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret
SECRET=your_session_secret
```

> 🔒 Keep your `.env` file private and never commit it to version control.

---

### 3. Install Dependencies

```bash
npm install
```

---

### 4. Start the Application

```bash
nodemon app.js
```

The app should now be running at:

```
http://localhost:8080
```

---

## 📦 Project Structure

```
HopnStay/
├── models/             # Mongoose schemas
├── routes/             # Express routes
├── views/              # EJS templates
├── public/             # Static assets
├── app.js              # Main Express server
├── .env                # Environment variables
├── package.json        # NPM config
└── README.md
```

---

## 🌐 External Services

This project uses:

- **MongoDB Atlas** or local MongoDB
- **Cloudinary** for image hosting
- **Express + EJS** for rendering dynamic pages
- **Session-based authentication**

---

## 🧑‍💻 Developer Tips

- Use `console.log()` liberally when debugging routes or controllers.
- If MongoDB fails to connect, ensure your service is running with `mongod`.
- You can change the port in `app.js` if 8080 is already in use.

---

## 📬 Support

Having trouble? Open an issue or reach out to the project maintainer.

---

## 🌍 Happy Traveling with HopnStay!

> ✈️ Ready to explore the world, one stay at a time.

---
