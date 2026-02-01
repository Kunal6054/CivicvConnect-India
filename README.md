# 🇮🇳 Civic Connect India

> **Empowering Communities, Enabling Governance.**
> A modern civic engagement platform built with React, TypeScript, and Shadcn UI.

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

## 📖 Overview

**Civic Connect India** is a comprehensive web platform designed to bridge the gap between citizens and local administration. It allows users to report civic issues (like potholes, sanitation, or streetlights) with precise geolocation and provides officials with an analytics dashboard to track resolution progress.


Built for performance and accessibility using the latest web standards.

## ✨ Key Features

* **📍 Interactive Maps:** View and pin issues on a real-time map. Powered by **Leaflet** & **React-Leaflet**.
* **📊 Analytics Dashboard:** Visual insights on reported vs. resolved cases using **Recharts**.
* **📝 Smart Reporting:** Robust forms with validation using **React Hook Form** & **Zod**.
* **🎨 Modern UI:** Accessible and beautiful components built with **Shadcn UI** & **Radix Primitives**.
* **⚡ Blazing Fast:** Optimized build and hot-reloading powered by **Vite**.
* **🔔 Real-time Feedback:** Instant toast notifications using **Sonner**.

## 🛠️ Tech Stack

This project uses a modern stack focused on developer experience and performance:

* **Framework:** [React](https://reactjs.org/) + [Vite](https://vitejs.dev/)
* **Language:** [TypeScript](https://www.typescriptlang.org/)
* **Styling:** [Tailwind CSS](https://tailwindcss.com/) + [Shadcn UI](https://ui.shadcn.com/)
* **Maps:** [Leaflet](https://leafletjs.com/)
* **State & Data:** [TanStack Query](https://tanstack.com/query/latest)
* **Forms:** [React Hook Form](https://react-hook-form.com/) + [Zod](https://zod.dev/)
* **Icons:** [Lucide React](https://lucide.dev/)
* **Animations:** [Framer Motion](https://www.framer.com/motion/)

## 🚀 Getting Started

### Prerequisites

Ensure you have Node.js installed on your machine.

### Installation

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/your-username/civic-connect-india.git](https://github.com/your-username/civic-connect-india.git)
    cd civic-connect-india
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Start the development server**
    ```bash
    npm run dev
    ```

4.  **Build for production**
    ```bash
    npm run build
    ```

## 📂 Project Structure

```text
src/
├── components/       # Shadcn UI & Custom components
├── hooks/           # Custom React hooks (use-toast, etc.)
├── pages/           # Route pages (Dashboard, Home, Map)
├── lib/             # Utility functions (utils.ts)
├── assets/          # Static images
└── App.tsx          # Main application entry
