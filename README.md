# 🌐 Portfolio

A personal portfolio built with **React**, **Three.js**, and **React Three Fiber** — featuring immersive 3D visuals and smooth multi-page navigation.

---

## ✨ Features

- 3D interactive scenes powered by Three.js & R3F
- Multi-page routing with React Router
- Smooth animations and transitions
- Fully responsive layout
- Deployed on Vercel

---

## 🛠️ Tech Stack

| Layer | Tech |
|---|---|
| Framework | React + Vite |
| 3D Engine | Three.js + React Three Fiber |
| Helpers | @react-three/drei |
| Routing | React Router DOM |
| Deployment | Vercel |

---

## 🚀 Getting Started

**Prerequisites:** Node.js (LTS) and Git installed.

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/portfolio.git
cd portfolio

# Install dependencies
npm install

# Start dev server
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

---

## 📁 Project Structure

```
src/
├── components/     # Reusable UI components
├── pages/          # Route-level pages (Home, About, Projects, Contact)
├── three/          # Three.js scenes and 3D assets
├── App.jsx         # Router setup
└── main.jsx        # Entry point
```

---

## 📦 Build for Production

```bash
npm run build
```

Output goes to the `dist/` folder.

---

## 🌍 Deployment

This project is deployed on **Vercel**. Every push to `main` triggers an automatic redeploy.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com)

---

## 📄 License

MIT — do whatever you want with it.
