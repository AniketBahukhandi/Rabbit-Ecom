# 🐇 Rabbit – E-Commerce Clothing Store

Rabbit is a modern, full-stack E-Commerce platform built for selling clothes online. It features a PayPal payment gateway, an admin panel for managing products, orders, and users, and a sleek, responsive design for a seamless shopping experience.

---

## 🚀 Features

### 🛍 Storefront
- Browse and search clothing products by category, gender, or keyword.
- View detailed product pages with images, descriptions, and pricing.
- Add products to the shopping cart and update quantities.
- Secure checkout process with PayPal integration.
- Mobile-friendly, responsive design.

### 🔐 Authentication
- User registration & login.
- Secure password hashing.
- Profile management and order history.

### 🛠 Admin Panel
- Add, edit, or delete products.
- Manage inventory and product images.
- View and update orders.
- Manage user accounts.

### 💳 Payment Integration
- PayPal payment gateway for secure transactions.
- Supports both sandbox (testing) and live modes.

---

## 🖼 Tech Stack

### Frontend:
- React.js / Next.js
- Tailwind CSS / Bootstrap for styling
- Axios for API calls

### Backend:
- Node.js + Express.js
- MongoDB with Mongoose ORM
- JSON Web Token (JWT) for authentication

### Payments:
- PayPal REST API integration

### Other Tools:
- Multer for image uploads
- Cloud storage (e.g., Cloudinary) for media management

---

## 📦 Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/AniketBahukhandi/Rabbit-Ecom.git
cd rabbit-ecom
```

### 2️⃣ Backend Setup
```bash
cd backend
npm install
```
Create a `.env` file inside the `backend` directory with:
```env
MONGO_URI= 
PORT=5000
JWT_SECRET=rabbit_ecomm_jwt_secret_2024_aniket_bahukhandi_super_secure_key_xyz789
NODE_ENV=development 

CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
```
Run the backend:
```bash
npm run dev
```

### 3️⃣ Frontend Setup
```bash
cd ../frontend
npm install
```
Create a `.env` file inside the `frontend` directory with:
```env
VITE_BACKEND_URL=
VITE_PAYPAL_CLIENT_ID=
```
Run the frontend:
```bash
npm start
```

---

## 📂 Project Structure
```plaintext
rabbit-ecom/
│── backend/        # Node.js + Express API
│── frontend/       # React.js client
│── README.md       # Project documentation
```

---

## 🧑‍💻 Contributing
1. Fork the repository.
2. Create your feature branch:
    ```bash
    git checkout -b feature-name
    ```
3. Commit your changes:
    ```bash
    git commit -m 'Add feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature-name
    ```
5. Create a pull request.

---
