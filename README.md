# 🎨 Imagify

A full-stack AI-powered image generation web application built with the MERN stack. Users can generate AI images from text prompts, manage credits, and securely purchase additional credits using Razorpay.

🌐 **Live Demo:** https://imagify-psi-brown.vercel.app/

---

## 📸 Screenshots

### 🏠 Home Page
<img width="1341" height="632" alt="image" src="https://github.com/user-attachments/assets/0a699d16-2fba-4c50-b683-ddf79c86697e" />


### 🔐 Login
<img width="1187" height="613" alt="image" src="https://github.com/user-attachments/assets/8606d34c-d030-443d-8edc-e62a9d5c4cd7" />


### 🎨 Image Generation
<img width="1331" height="584" alt="image" src="https://github.com/user-attachments/assets/b7bb25f9-9f62-4cb4-94de-8d49e1ee41a5" />

<img width="1175" height="586" alt="image" src="https://github.com/user-attachments/assets/1e1e0ede-879f-4bb5-88a6-510b16d2259e" />


### 💳 Pricing & Credits
<img width="1208" height="615" alt="image" src="https://github.com/user-attachments/assets/27620d87-eac0-432e-99a4-8cb4ecd4efe9" />


---

# ✨ Features

- 🔐 JWT-based User Authentication
- 🎨 AI Image Generation from Text Prompts
- 💰 Credit-Based Image Generation System
- 💳 Razorpay Payment Gateway Integration
- 📥 Download Generated Images
- 📱 Fully Responsive User Interface
- ☁️ MongoDB Atlas Database
- ⚡ RESTful Backend API
- 🌐 Deployed on Vercel & Render

---

# 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS
- Axios
- React Router

### Backend
- Node.js
- Express.js
- JWT Authentication
- Mongoose

### Database
- MongoDB Atlas

### AI
- ClipDrop API

### Payments
- Razorpay

### Deployment
- Vercel (Frontend)
- Render (Backend)

---

# 📂 Project Structure

```
imagify
│
├── client
│   ├── public
│   ├── src
│   │   ├── assets
│   │   ├── components
│   │   ├── context
│   │   ├── pages
│   │   └── App.jsx
│   └── package.json
│
└── server
    ├── config
    ├── controllers
    ├── middlewares
    ├── models
    ├── routes
    ├── server.js
    └── package.json
```

---

# ⚙️ Installation

## Clone the Repository

```bash
git clone https://github.com/crazyluhsnap/imagify.git

cd imagify
```

---

## Backend Setup

```bash
cd server

npm install

npm start
```

---

## Frontend Setup

```bash
cd client

npm install

npm run dev
```

---

# 🔑 Environment Variables

## Backend (`server/.env`)

```env
MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

CLIPDROP_API=your_clipdrop_api_key

RAZORPAY_KEY_ID=your_razorpay_key_id

RAZORPAY_KEY_SECRET=your_razorpay_key_secret

CURRENCY=INR
```

---

## Frontend (`client/.env`)

```env
VITE_BACKEND_URL=your_backend_url

VITE_RAZORPAY_KEY_ID=your_razorpay_key_id
```

---

# 🚀 How It Works

1. User creates an account or logs in.
2. JWT authentication verifies the user.
3. User enters a text prompt.
4. Backend sends the prompt to the ClipDrop API.
5. Generated image is returned to the frontend.
6. One credit is deducted for every generated image.
7. Users can purchase additional credits using Razorpay.

---

# 📌 API Endpoints

## User

- Register
- Login
- Get User Credits

## Image

- Generate Image

## Payment

- Create Razorpay Order
- Verify Payment

---

# 📈 Future Improvements

- 🖼️ Image Generation History
- 🌙 Dark Mode
- 📤 Share Generated Images
- 📝 Prompt Templates
- ❤️ Favorite Images
- 👤 User Dashboard
- 📊 Usage Analytics

---

# 🌍 Deployment

| Service | Platform |
|----------|----------|
| Frontend | Vercel |
| Backend | Render |
| Database | MongoDB Atlas |

---

# 👨‍💻 Author

**Panshul Gupta**

GitHub: https://github.com/crazyluhsnap

LinkedIn: https://www.linkedin.com/in/panshul-gupta-4b1617278/

---
