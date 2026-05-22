# Task Manager App 📝

A React application that allows users to manage their daily tasks, including adding, viewing, and organizing tasks efficiently using form validation.

## Project Creation & Setup

This project was initialized using Vite. Here are the steps to recreate or set it up:

### 1. Initialize the Vite Project
```bash
npm create vite@latest Task-Manager-App -- --template react
cd Task-Manager-App
```

### 2. Install Core Dependencies
Install standard Vite dependencies:
```bash
npm install
```

### 3. Install Additional Packages
This project requires Tailwind CSS for styling and React Hook Form for handling form inputs:
```bash
npm install @tailwindcss/vite react-hook-form
```

### 4. Running the Application
Start the development server:
```bash
npm run dev
```
Open your browser and visit the local URL provided in the terminal (usually `http://localhost:5173`).

## Packages Used & Their Functionalities

- **`react` & `react-dom`**: The foundational libraries for building interactive user interfaces.
- **`react-hook-form`**: A performant and flexible library for managing form state and validation, minimizing re-renders.
- **`@tailwindcss/vite`**: The official Vite plugin for integrating Tailwind CSS to style the application easily.
- **`vite`**: The incredibly fast frontend tooling used for local development and optimized production builds.

## Features

- **Add Tasks:** Create new tasks with ease using a controlled and validated form.
- **Form Validation:** Ensures required task details are entered correctly before submission using `react-hook-form`.
- **Responsive UI:** Fully responsive design built with Tailwind CSS, working smoothly on mobile and desktop.
