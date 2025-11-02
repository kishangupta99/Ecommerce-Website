# 🛒 Full-Stack E-Commerce Website

### Live Demo: [View Here 🚀](https://ecommerce-frontend-murex-alpha.vercel.app/)

A fully functional **E-Commerce Web Application** built using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js) with **real-time payments**, **secure authentication**, and **complete admin control**.  
It provides all essential features of a modern online store — from product browsing to order tracking and secure payments.

---

## 🚀 Tech Stack

| Layer | Technologies |
|--------|---------------|
| **Frontend** | React.js, Context-API, Tailwind CSS |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB, Mongoose |
| **Authentication** | JWT (JSON Web Tokens) |
| **Payment Gateway** | Razorpay / Stripe Integration |
| **Hosting** | Vercel (Frontend), Render / Railway (Backend) |

---

## ✨ Features

### 🧑‍💻 User Side
- 🔐 **Authentication:** Register, Login, Logout using JWT.
- 🛍️ **Product Listing:** Browse products with details, price, and category.
- 🧾 **Cart Management:** Add, update, and remove items from cart.
- 💳 **Secure Payments:** Razorpay / Stripe payment gateway integration.
- 📦 **Order Management:** Place and track your orders easily.
- ❤️ **Wishlist System:** Save products for later.
- 🔍 **Search & Filters:** Search products by name, category, or price.
- 📱 **Responsive Design:** Fully optimized for all devices.

### 🛠️ Admin Side
- 🧑‍💼 **Admin Dashboard:** Manage everything from one place.
- 🆕 **Add / Edit / Delete Products**
- 📊 **View Orders & Order Status Update**
- 👥 **Manage Users & Admins**
- 📈 **Sales Overview and Insights**

---

## 🏗️ Folder Structure

ecommerce/
├── backend/ # Express API
│ ├── models/ # Mongoose models
│ ├── routes/ # API routes
│ ├── controllers/ # Business logic
│ ├── middleware/ # Auth / Error handling
│ └── server.js # Entry point
│
├── frontend/ # React App
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── redux/
│ │ └── utils/
│ └── package.json
│
└── README.md




Setup Backend
cd backend
npm install


Create a .env file inside backend/:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret


Then run:

npm start

3️⃣ Setup Frontend
cd frontend
npm install
npm run dev


Visit 👉 http://localhost:5173/ to view the app locally.



💰 Payment Integration

Integrated Razorpay / Stripe for real-time and secure payments.

Supports both test and live modes.

Order details automatically update after successful transaction.

📸 Screenshots
Home Page	Product Page	Checkout

	
	

(Replace with your actual screenshots)

📧 Contact

Kishan Kumar Gupta
📩 Email: acpkishankumar@gmail.com

💻 GitHub: kishangupta99

⭐ Show Your Support

If you like this project, please ⭐ the repository and share it!
Your support keeps open-source projects alive ❤️


---

Would you like me to **customize this README** with:
- actual **backend repo link** (if deployed separately), and  
- your **Razorpay or Stripe** mention specifically (which one you used)?  

Then I’ll finalize a **perfect version for GitHub upload**.
