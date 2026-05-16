# 💻 PC Parts - 3D Catalog

#### Description:

The **PC Parts - 3D Catalog** is an interactive web application designed to expand your knowledge of computer hardware components. Built with **React** and styled using **Tailwind CSS**, this project aims to provide an engaging and educational experience through stunning 3D visualizations.

## 🌟 The Vision

Have you ever wondered what the inside of a computer looks like or what each part does? This project brings that curiosity to life. Instead of static images or text, you can explore detailed 3D models of essential PC components like the CPU, GPU, motherboard, and more. Our goal is to make learning about technology an intuitive and fun experience.

## ✨ Key Features

- **Interactive 3D Models:** Get up close and personal with realistic 3D models of various PC parts.
- **Detailed Information:** Click on any component to get a concise description of its function and importance.
- **Intuitive UI/UX:** A clean and modern interface, powered by Tailwind CSS, ensures a smooth and enjoyable user experience.
- **Educational Focus:** The application is designed to be a valuable resource for students, tech enthusiasts, and anyone curious about PC hardware.
- **Responsive Design (Mobile-Ready):** The application ensures a seamless experience across all devices, from large monitors to smartphones, adapting the layout and 3D controls for optimal viewing and touch interaction.

# PC Parts Catalog 3D

Interactive 3D catalog for exploring computer hardware parts.

> Built with **Next.js (App Router)**, **React Three Fiber**, **Three.js**, **Tailwind CSS**, and **Framer Motion**.

---

## ✨ What it does
- Renders real-time **3D models** (GLB) of PC components (CPU, motherboard, storage, networking, etc.).
- Lets users browse categories through a responsive **sidebar**.
- Supports an **immersive fullscreen** mode for detailed viewing.

---

## 🕹️ How to use
1. Open the app.
2. Use the **sidebar** to navigate between categories.
3. Click a category item to view its details.
4. Use **Open Fullscreen** to enter immersive mode.

---

## 🧱 Tech stack
- **Next.js**
- **React**
- **TypeScript**
- **Tailwind CSS**
- **react-three/fiber**
- **@react-three/drei**
- **Three.js**
- **Framer Motion**
- **GSAP**

---

## 🌍 Live demo
Deployed on Netlify: https://pc-parts-3d.netlify.app


---


## 🗂️ Project structure (high-level)
- `app/`
  - `layout.tsx`, `page.tsx`
  - route groups like `/(root)` and `/(pages)`
- `app/components/`
  - UI components (Navbar, Sidebar, Modals)
  - 3D components under `app/components/canvas/`

---

## 📦 Assets
3D models are loaded from `public/models/` (GLB files).

---

## Notes
This project is designed for learning and exploration—3D models are for illustrative purposes.


