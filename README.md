# RoomGuru

# 🏠 RoomGuru – Student Room Finder Platform

RoomGuru is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) web application that helps students easily find affordable rooms when relocating to new cities. It offers secure authentication, listing creation, booking features, and a modern, responsive 

## 🚀 Features
- 🔐 **Authentication & Authorization** – Sign up & login with JWT and Bcrypt.
- 🏠 **Listing Management** – Create new property listings with detailed info.
- 🖼️ **Photo Upload** – Drag & drop image upload, delete functionality, stored in MongoDB.
- 📅 **Booking System** – Integrated calendar-based booking interface.
- 🔍 **Search & Filter** – Search listings by keyword or filter by category.
- 💖 **Wishlist** – Add or remove favorite listings.
- 📦 **State Management** – Redux used for global state control.
- 🎨 **Styling** – Styled using SCSS (Sass) and Material UI components.

## 🛠️ Tech Stack

- **Frontend:** React.js, Redux, Material UI, SCSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose)
- **Auth:** JWT, Bcrypt
- **Tools:** Git, GitHub, VS Code
## 📸 Video
https://drive.google.com/file/d/1uDr9tyOJ9sh2D79iirhHb8_T6jy0Epz2/view?usp=sharing

##  Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/roomguru.git
   cd roomguru
2. **Install dependencies**
   cd client
   npm install
   cd server
   npm install
3. **Environment Variables**
Create a .env file in the server/ directory with:
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret

4.**Start the app**
# Start backend
cd server
npm start

# Start frontend
cd ../client
npm start

