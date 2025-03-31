# Blog Website

## 📌 Overview
This is a **React-based blog platform** that provides information about different countries using the **REST Countries API**. Users can explore details like population, borders, and regions, interact with a **Google Map**, and engage with blog posts by **liking and commenting**.

## ✨ Features
- 🌍 **Explore Country Data** – Fetch and display country details (name, region, population, borders)
- 🗺 **Google Maps Integration** – Interactive maps to visualize locations
- 💬 **Engage with Blogs** – Like and comment on blog posts
- ⚡ **State Management** – Uses Redux Toolkit for efficient global state handling
- 🎨 **Modern UI** – Responsive design with Tailwind CSS

## 🛠 Technologies Used
- **Frontend**: React, Redux Toolkit, Tailwind CSS
- **APIs**: REST Countries API, Google Maps API
- **State Management**: Redux Toolkit
- **Icons**: React Icons

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/purbakundu/Blogwebvite
cd Bloging
```

### 2️⃣ Install Dependencies
```sh
npm install
```

### 3️⃣ Set Up Environment Variables
Create a **.env** file in the root directory and add:
```env
VITE_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
```

### 4️⃣ Run the Development Server
```sh
npm run dev
```
The application will be available at **http://localhost:5174/**.

## 📂 Project Structure
```
📦 src
 ┣ 📂 components
 ┃ ┣ 📜 BlogPost.jsx       # Blog Post Component
 ┃ ┣ 📜 MapContainer.jsx   # Google Maps Component
 ┣ 📂 redux
 ┃ ┣ 📜 blogSlice.js       # Redux Slice for Blogs
 ┣ 📜 App.jsx              # Main App Component
 ┣ 📜 main.jsx             # Entry Point
```

## 📜 License
This project is open-source and available under the **MIT License**.

