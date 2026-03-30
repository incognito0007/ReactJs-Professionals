# 🍕 Padre Gino's – React Application

A modern React-based web application built using **Vite**, **TanStack Router**, and **React Query**.
This project demonstrates scalable frontend architecture with routing, API handling, and UI components.

---

## 🚀 Features

* ⚡ Fast development with Vite
* 🔄 Data fetching using React Query
* 🧭 File-based routing using TanStack Router
* 🎨 Modern UI components
* 📦 Modular and scalable folder structure

---

## 🛠️ Tech Stack

* React
* Vite
* @tanstack/react-router
* @tanstack/react-query
* JavaScript / TypeScript
* CSS / Tailwind (if used)

---

## 📂 Project Structure

```
padre-ginos/
│── src/
│   ├── api/                # API calls
│   ├── routes/             # Route files (TanStack Router)
│   ├── components/         # Reusable components
│   ├── Modal.jsx
│   ├── ErrorBoundary.jsx
│   └── main.jsx
│
│── index.html
│── package.json
│── vite.config.js
```

---

## ⚙️ Prerequisites

Make sure you have installed:

* Node.js (v18 or above recommended)
* npm or yarn

Check versions:

```
node -v
npm -v
```

---

## 📥 Installation

Clone the repository:

```
git clone https://github.com/incognito0007/ReactJs-Professionals.git
```

Navigate to the project folder:

```
cd ReactJs-Professionals/padre-ginos
```

Install dependencies:

```
npm install
```

---

## ▶️ Running the Application

Start the api server:

```
cd .\citr-v9-project-main\api
npm run dev
```

Start the development server:

```
cd .\citr-v9-project-main\padre-ginos\
npm run dev
```

👉 Open your browser and go to:

```
http://localhost:5173
```

---

## 🧪 Running Tests (Optional)

If using Vitest:

```
npx vitest
```

For coverage:

```
npx vitest run --coverage
```

---

## 🛠️ Build for Production

```
npm run build
```

Preview production build:

```
npm run preview
```

---

## ❗ Troubleshooting

### 1. routeTree.gen not generating

* Ensure `@tanstack/router-plugin` is installed
* Check `vite.config.js` configuration
* Restart dev server

### 2. Dependency errors (ERESOLVE)

* Delete `node_modules` and `package-lock.json`
* Run:

```
npm install
```

### 3. Port already in use

Change port:

```
npm run dev -- --port=3000
```

---

## 📌 Notes

* This project uses modern React features like Suspense and hooks.
* Make sure dependencies are properly installed before running.

---

## 👨‍💻 Author

**Ankit Anand**

---

## ⭐ Contribute

Feel free to fork the repo and submit pull requests!

---
