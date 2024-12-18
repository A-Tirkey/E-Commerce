# 🛍️ E-Commerce Platform

An advanced, scalable, and user-friendly full-stack e-commerce platform designed for seamless online shopping experiences. This application integrates robust backend technologies, a secure authentication system, and a visually appealing frontend interface.

## 🚀 Features

- 🗄️ **MongoDB & Redis Integration**: Efficient database management and caching for faster load times.
- 💳 **Stripe Payment Setup**: Secure and seamless payment processing.
- 🔐 **Robust Authentication System**: Ensures data security with JWT-based access and refresh tokens.
- 📝 **User Signup & Login**: Simple and secure user registration and authentication.
- 🛒 **E-Commerce Core**:
  - 📦 **Product & Category Management**
  - 🛍️ **Shopping Cart Functionality**
  - 💰 **Checkout with Stripe**
- 🏷️ **Coupon Code System**: Add discounts to boost sales.
- 👑 **Admin Dashboard**: Manage products, users, and sales efficiently.
- 📊 **Sales Analytics**: Gain insights with real-time sales data.
- 🎨 **TailwindCSS Design**: Modern and responsive UI/UX.
- 🔒 **Security**: Implements data protection and secure transactions.
- 🚀 **Caching with Redis**: Optimized performance for frequent operations.
- ⌛ **And More**: Expandable features for future enhancements.

---

## 📄 Setup Instructions

### 1️⃣ Configure Environment Variables
Create a `.env` file in the root directory and add the following configurations:

```bash
PORT=5000
MONGO_URI=your_mongo_uri
UPSTASH_REDIS_URL=your_redis_url
ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
CLIENT_URL=http://localhost:5173
NODE_ENV=development
