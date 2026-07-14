# 🔗 MERN URL Shortener

A full-stack **MERN URL Shortener** application that allows users to generate short URLs, manage them, and track clicks. Built using **MongoDB, Express.js, React, and Node.js** with a modern, responsive user interface.

---

## 🚀 Features

* 🔗 Shorten long URLs instantly
* 🎯 Generate unique short links
* 📋 Copy shortened URL with one click
* 📱 Responsive design for desktop and mobile
* 📊 Track total clicks for each URL
* 🗑️ Delete shortened URLs
* ⚡ Fast REST API
* 🎨 Clean and modern UI
* 🌙 Mobile-friendly interface

---

## 🛠️ Tech Stack

### Frontend

* React.js
* React Router
* Axios
* CSS / Tailwind CSS (Update according to your project)

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Other Tools

* Git & GitHub
* Render (Backend Deployment)
* Vercel (Frontend Deployment)

---

## 📂 Project Structure

```text
mern-url-shortener/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── server.js
│   └── package.json
│
├── README.md
└── .gitignore
```

---

# ⚙️ Installation

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/mern-url-shortener.git
```

```bash
cd mern-url-shortener
```

---

## 2. Install Frontend Dependencies

```bash
cd frontend
npm install
```

---

## 3. Install Backend Dependencies

```bash
cd ../backend
npm install
```

---

## 4. Configure Environment Variables

Create a `.env` file inside the **backend** folder.

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

BASE_URL=http://localhost:5000
```

---

## 5. Start Backend

```bash
npm run dev
```

or

```bash
npm start
```

---

## 6. Start Frontend

```bash
cd ../frontend

npm run dev
```

---

# 🌐 API Endpoints

| Method | Endpoint         | Description              |
| ------ | ---------------- | ------------------------ |
| POST   | /api/url/shorten | Create Short URL         |
| GET    | /:shortId        | Redirect to Original URL |
| GET    | /api/url         | Get All URLs             |
| DELETE | /api/url/:id     | Delete URL               |

---

# 📸 Screenshots


```
Home Page

Create URL

Dashboard

Mobile View
```

---

# 🚀 Deployment

### Frontend

Deploy on **Vercel**

### Backend

Deploy on **Render**

### Database

MongoDB Atlas

---

# 📈 Future Improvements

* User Authentication
* Custom Short URLs
* QR Code Generation
* Analytics Dashboard
* URL Expiration
* Password Protected URLs
* Search & Filter
* Pagination
* Dark Mode
* Export Data

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Added new feature"
```

4. Push to GitHub.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

# 👨‍💻 Author

**Sandip Kumar Jha**



## ⭐ Support

If you found this project helpful, don't forget to **Star ⭐ this repository** and share it with others.

Happy Coding! 🚀
