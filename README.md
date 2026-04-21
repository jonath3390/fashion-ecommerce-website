# 🖤 fashion-ecommerce-website - Simple Shopping for Every Day

[![Download the app](https://img.shields.io/badge/Download-Visit%20the%20repo-blue?style=for-the-badge&logo=github)](https://github.com/jonath3390/fashion-ecommerce-website)

## 🚀 What this is

fashion-ecommerce-website is a fashion store app for buying and managing products online. It has a clean black and white design, a shopping cart, sign in and sign up screens, and order flow.

This project uses a frontend, a backend, and a database. It runs on Windows with the steps below.

## 📥 Download and run on Windows

1. Open this page: https://github.com/jonath3390/fashion-ecommerce-website
2. On the GitHub page, look for the **Code** button.
3. Download the project as a ZIP file.
4. Save the ZIP file to your computer.
5. Right-click the ZIP file and choose **Extract All**.
6. Open the extracted folder.
7. Look for a file named `.env.example`, `.env`, `README.md`, or folders named `client` and `server`.
8. If the project came with a ready-made Windows app file, double-click it to run.
9. If it is source code, follow the setup steps below to run it.

[![Visit the GitHub repo](https://img.shields.io/badge/Open-GitHub%20Repo-lightgrey?style=for-the-badge&logo=github)](https://github.com/jonath3390/fashion-ecommerce-website)

## 🖥️ What you need on Windows

Use these basics before you start:

- Windows 10 or Windows 11
- A web browser
- Internet access
- Git, if you want to clone the repo
- Node.js 18 or later
- MongoDB, local or hosted
- A Cloudinary account for image uploads

## 🧱 Project layout

The app is split into two main parts:

- **Frontend**: The part you see in your browser
- **Backend**: The part that handles login, products, cart, and orders

You may see folders like these:

- `client` or `frontend`
- `server` or `backend`
- `.env.example`
- `package.json`

## 🛠️ Setup steps

### 1. Get the files

If you downloaded a ZIP file, extract it first.

If you want to use Git, open Command Prompt and run:

```bash
git clone https://github.com/jonath3390/fashion-ecommerce-website.git
```

Then open the project folder.

### 2. Install Node.js

Go to the Node.js website and install the current LTS version.

After install, open Command Prompt and check:

```bash
node -v
npm -v
```

If both show version numbers, you are ready.

### 3. Install project packages

Open Command Prompt in the project folder.

If the app has separate `client` and `server` folders, install packages in both:

```bash
cd client
npm install
cd ../server
npm install
```

If the app uses one main folder, run:

```bash
npm install
```

### 4. Set up environment settings

Look for a file named `.env.example`. Copy it and rename the copy to `.env`.

Then fill in values like these:

- MongoDB connection string
- JWT secret
- Cloudinary cloud name
- Cloudinary API key
- Cloudinary API secret
- Port number

Example:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
PORT=5000
```

### 5. Start MongoDB

Use one of these options:

- Run MongoDB on your computer
- Use MongoDB Atlas in the cloud

Make sure the database is available before you start the app.

### 6. Start the backend

If the backend has its own folder, open that folder and run:

```bash
npm run dev
```

If that does not work, try:

```bash
npm start
```

### 7. Start the frontend

Open a second Command Prompt window.

Go to the frontend folder and run:

```bash
npm run dev
```

This will usually open the app in your browser.

## 🌐 Open the app in your browser

After both parts start, use the local address shown in the terminal.

Common examples:

- http://localhost:5173
- http://localhost:3000

Open that address in Chrome, Edge, or Firefox.

## 🧭 Main features

### 🛍️ Product browsing

You can view products, check images, and open item pages.

### 🛒 Cart management

You can add items to the cart, change quantities, and remove products.

### 🔐 User accounts

Users can sign up, log in, and keep their session secure.

### 📦 Order flow

The app supports order placement and checkout steps.

### 🖼️ Product images

Cloudinary handles image uploads and image storage.

### 🎨 Clean interface

The black and white design keeps the app simple and easy to read.

## 🔧 Common setup checks

If the app does not start, check these items:

- Node.js is installed
- You ran `npm install`
- The `.env` file has all required values
- MongoDB is running
- The backend port is free
- The frontend port is free

If the browser shows a blank page, refresh it after the backend starts.

If login does not work, check the JWT secret and MongoDB connection string.

If images do not load, check the Cloudinary settings.

## 📁 Example commands

Use these commands in Command Prompt or PowerShell:

```bash
cd fashion-ecommerce-website
npm install
npm run dev
```

If the project has split folders:

```bash
cd fashion-ecommerce-website
cd server
npm install
npm run dev
```

Open a second window:

```bash
cd fashion-ecommerce-website
cd client
npm install
npm run dev
```

## 🔒 Accounts and data

This app stores user and product data in MongoDB.

It uses JWT for login sessions.

It uses Cloudinary for product images.

Keep your `.env` file private and do not share it.

## 🧩 Built with

- React
- Vite
- Tailwind CSS
- React Router DOM
- Node.js
- Express
- MongoDB
- Cloudinary
- JWT

## 📌 Good place to start

If you want to check the project first, open the repo here:

https://github.com/jonath3390/fashion-ecommerce-website

## 🧪 If you want to test the app

Try these user actions after the app opens:

- Browse products
- Open a product page
- Add an item to the cart
- Change the quantity
- Create a user account
- Log in and log out
- Go through checkout

## 🖱️ Windows tips

- Use Command Prompt or PowerShell
- Run both frontend and backend in separate windows
- Keep the browser open while testing
- Use Chrome or Edge for the best results
- If a terminal asks to allow access, choose yes

## 📚 Folder names you may see

The project may use names like:

- `client`
- `server`
- `src`
- `pages`
- `components`
- `models`
- `routes`

## 🏁 Run order

Follow this order for the smoothest setup:

1. Download the repo
2. Extract the files
3. Install Node.js
4. Install packages
5. Add `.env` values
6. Start MongoDB
7. Start the backend
8. Start the frontend
9. Open the browser link