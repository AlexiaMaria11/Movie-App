<div align="center">
  <br />
  <a href="https://www.youtube.com/watch?v=dCLhUialKPQ" target="_blank">
    <img src="public/readme/hero.png" alt="Project Banner">
  </a>
  <br />

  <div>
    <img src="https://img.shields.io/badge/-React_JS-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="react.js" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
  </div>

  <h3 align="center">Movie Application</h3>
</div>

---

## 📋 Table of Contents
1. [Introduction](#introduction)
2. [Tech Stack](#tech-stack)
3. [Features](#features)
4. [Quick Start](#quick-start)
5. [Environment Variables](#environment-variables)

---

## 🤖 Introduction

This Movie App allows users to browse trending movies, search for specific titles, and explore content using the TMDB API.  

Built with:  
- **React.js** for the frontend  
- **Appwrite** for backend services  
- **Tailwind CSS** for styling  

The app is fully responsive and features a modern, sleek UI.

---

## ⚙️ Tech Stack

- **React.js** – UI library for building interactive interfaces  
- **Appwrite** – Backend as a Service (authentication, database, storage)  
- **Tailwind CSS** – Utility-first CSS framework for responsive design  
- **React-use** – Hooks library for React  
- **Vite** – Fast frontend build tool  

---

## 🔋 Features

- Browse all available movies  
- Search for movies by title  
- Trending movies based on search counts  
- Modern and responsive UI  
- Easily extendable code architecture  

---

## 🤸 Quick Start

**Prerequisites:**

- [Git](https://git-scm.com/)  
- [Node.js](https://nodejs.org/)  
- [npm](https://www.npmjs.com/)  

**Clone the Repository:**

```bash
git clone https://github.com/AlexiaMaria11/Movie-App.git
cd Movie-App

```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
VITE_TMDB_API_KEY=

VITE_APPWRITE_PROJECT_ID=
VITE_APPWRITE_DATABASE_ID=
VITE_APPWRITE_COLLECTION_ID=
```

Replace the placeholder values with your actual **[TheMovieDatabase API](https://developer.themoviedb.org/reference/intro/getting-started)** and **[Appwrite](https://apwr.dev/JSM050)** credentials.

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the project.
