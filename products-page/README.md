# Products Page 🛒

A React application for displaying a grid or list of products, complete with responsive design and modern styling.

## Project Creation & Setup

This project was built using Vite. Here is how to create it from scratch:

### 1. Initialize the Vite Project
```bash
npm create vite@latest products-page -- --template react
cd products-page
```

### 2. Install Core Dependencies
Install the default React dependencies:
```bash
npm install
```

### 3. Install Additional Packages
This project utilizes Tailwind CSS for styling:
```bash
npm install @tailwindcss/vite
```

### 4. Running the Application
Start the development server:
```bash
npm run dev
```
Open your browser and visit the local URL provided in the terminal (usually `http://localhost:5173`).

## Packages Used & Their Functionalities

- **`react` & `react-dom`**: The fundamental libraries for constructing the UI and managing the component lifecycle.
- **`@tailwindcss/vite`**: The modern Vite plugin for Tailwind CSS, providing utility classes for rapid and responsive UI design.
- **`vite`**: A lightning-fast development server and optimized build tool for React applications.

## Features

- **Product Display:** Renders a list or grid of various products with their details (image, name, price, description).
- **Responsive Layout:** Adjusts seamlessly across different screen sizes using Tailwind CSS utilities.
- **Modern UI:** Clean, intuitive, and visually appealing product cards.
