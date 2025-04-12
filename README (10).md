# 🚀 Project Setup Guide

## 📁 Project Structure

```
.
├── backend/
├── public/
├── src/
├── README.md
├── index.html
├── package.json
├── package-lock.json
├── tailwind.config.js
├── postcss.config.js
├── tsconfig.json
├── tsconfig.app.json
├── tsconfig.node.json
├── eslint.config.js
```

## 🛠️ How to Run the Project

### 📦 Prerequisites

Make sure you have the following installed:

- Node.js (v16 or higher)
- npm or yarn
- MongoDB Atlas account

### ⚙️ Setup Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Install Dependencies**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Configure Environment Variables**

   Create the following environment files in the root of the project:

   ### `.env.local`

   ```env
   MONGO_URI=your_mongo_uri_here
   VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key
   VITE_ZEGOCLOUD_APPID=your_zegocloud_app_id
   VITE_ZEGOCLOUD_SERVER_SECRET=your_zegocloud_server_secret
   VITE_ZEGO_APP_ID=your_zego_app_id
   VITE_ZEGO_SERVER_URL=your_zego_server_url
   ```

   ### `.env`

   ```env
   VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key
   VITE_ZEGOCLOUD_APPID=your_zegocloud_app_id
   VITE_ZEGOCLOUD_SERVER_SECRET=your_zegocloud_server_secret
   ```

   📝 **Note**: Place these `.env` files in the **root directory** of your project (same level as `package.json`).

4. **Run the Development Server**

   ```bash
   npm run dev
   ```

   The app will be available at `http://localhost:5173` by default.

## 🌟 Features

- Clerk authentication integration
- ZegoCloud video/audio services
- MongoDB for backend database
- TailwindCSS styling
- TypeScript support

## 🧾 License

This project is licensed under the [MIT License](./LICENSE).
