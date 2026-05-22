# Country Explorer 🌍

A React application that fetches and displays information about countries from the [REST Countries API](https://restcountries.com/). Users can view a list of countries and filter them by name using a search bar.

## Project Creation & Setup

This project was created using Vite. Here is the step-by-step process from scratch:

### 1. Initialize the Vite Project
```bash
npm create vite@latest country-explorer -- --template react
cd country-explorer
```

### 2. Install Core Dependencies
Install the default dependencies provided by Vite:
```bash
npm install
```

### 3. Install Additional Packages
This project uses Tailwind CSS via the Vite plugin:
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

- **`react` & `react-dom`**: The core libraries for building the user interface using React components.
- **`@tailwindcss/vite`**: A Vite plugin to seamlessly integrate Tailwind CSS, allowing for utility-first styling with high performance.
- **`vite`**: The build tool and development server, offering extremely fast Hot Module Replacement (HMR).

## Features

- **Country Data Fetching:** Fetches country details (name, capital, population, region, flags) from an external API.
- **Search Functionality:** Filter countries in real-time by typing in the search bar.
- **Responsive UI:** Styled using Tailwind CSS for a clean and responsive user interface.
- **Loading & Error States:** Displays appropriate messages while data is being fetched or if an error occurs.
