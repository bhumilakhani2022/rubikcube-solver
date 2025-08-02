# Rubik's Cube Solver

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">
</p>

A modern, visually stunning Rubik's Cube solver and practice tool, built with React, TypeScript, and Vite. This application provides an interactive and engaging experience for cube enthusiasts of all skill levels.

## 🚀 Live Demo

[View the live demo here](https://rubikcube-solver.vercel.app/)

## ✨ Key Features

*   **Interactive Cube:** A fully interactive 3D and 2D Rubik's Cube that you can manipulate and solve.
*   **Practice Mode:** Scramble the cube and time your solves to track your progress and improve your speed.
*   **Statistics:** Keep track of your solve count, average time, and personal bests.
*   **Pattern Library:** Explore and apply various interesting cube patterns.
*   **Responsive Design:** A clean and modern UI that works seamlessly on all devices.

## 🛠️ Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

*   Node.js (v14 or later)
*   npm

### Installation

1.  Clone the repo
    ```sh
    git clone https://github.com/your_username/rubikcube-solver-main.git
    ```
2.  Install NPM packages
    ```sh
    npm install
    ```
3.  Start the development server
    ```sh
    npm run dev
    ```

## 📂 Project Structure

```
rubikcube-solver-main/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── components/
│   │   ├── CubeInput.tsx
│   │   ├── CubeView.tsx
│   │   └── InteractiveCube.tsx
│   ├── styles/
│   │   └── theme.css
│   ├── App.css
│   ├── App.tsx
│   ├── Cube.ts
│   ├── cubejs.d.ts
│   ├── index.css
│   ├── main.tsx
│   └── vite-env.d.ts
├── .gitignore
├── index.html
├── package.json
├── README.md
└── vite.config.ts
