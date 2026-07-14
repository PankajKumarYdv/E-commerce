# 🛒 MERN Stack eCommerce Website

A full-featured **eCommerce Web Application** built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. This application provides a seamless online shopping experience with user authentication, product management, shopping cart functionality, and secure order processing.

---

## 🚀 Features

### 👤 User Features
- User Registration & Login (JWT Authentication)
- Browse Products
- Search & Filter Products
- Product Details Page
- Add to Cart
- Update Cart Quantity
- Wishlist (Optional)
- Secure Checkout
- Order History
- User Profile Management

### 🛠️ Admin Features
- Admin Dashboard
- Manage Products (CRUD)
- Manage Users
- Manage Orders
- Update Order Status
- Dashboard Analytics

---

## 🛠️ Tech Stack

### Frontend
- React.js
- React Router
- Redux Toolkit / Context API
- Axios
- Bootstrap / Tailwind CSS

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Bcrypt.js

### Other Tools
- Cloudinary (Image Upload)
- Multer
- dotenv
- Git & GitHub

---

## 📂 Project Structure

```
ecommerce/
│
├── client/
│   ├── public/
│   ├── src/
│   └── package.json
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   └── server.js
│
├── .env
├── package.json
└── README.md
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/ecommerce-website.git
```

```bash
cd ecommerce-website
```

### Install Dependencies

#### Backend

```bash
cd server
npm install
```

#### Frontend

```bash
cd ../client
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file inside the `server` folder.

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

CLOUDINARY_NAME=your_cloudinary_name

CLOUDINARY_API_KEY=your_api_key

CLOUDINARY_API_SECRET=your_api_secret
```

---

## ▶️ Run the Project

### Start Backend

```bash
cd server
npm run dev
```

### Start Frontend

```bash
cd client
npm start
```

The application will run at:

Frontend:
```
http://localhost:3000
```

Backend:
```
http://localhost:5000
```

---
<!-- 

## 📸 Screenshots

> Add screenshots of your project here.

- Home Page
- Product Page
- Cart
- Checkout
- Admin Dashboard

-->
---

## 📌 Future Improvements

- Payment Gateway Integration (Stripe/Razorpay)
- Product Reviews & Ratings
- Wishlist
- Coupons & Discounts
- Email Notifications
- Inventory Management
- Multi-language Support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature/NewFeature
```

3. Commit your changes

```bash
git commit -m "Add New Feature"
```

4. Push to the branch

```bash
git push origin feature/NewFeature
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Your Name**

- GitHub: https://github.com/your-github-username
- LinkedIn: https://linkedin.com/in/your-linkedin-username

---

⭐ If you found this project helpful, don't forget to **Star** the repository!
