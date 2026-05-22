# Country Explorer 🌍

A React application that fetches and displays information about countries from the [REST Countries API](https://restcountries.com/). Users can view a list of countries and filter them by name using a search bar.

## Features

- **Country Data Fetching:** Fetches country details (name, capital, population, region, flags) from an external API.
- **Search Functionality:** Filter countries in real-time by typing in the search bar.
- **Responsive UI:** Styled using Tailwind CSS for a clean and responsive user interface.
- **Loading & Error States:** Displays appropriate messages while data is being fetched or if an error occurs.

## Technologies Used

- **React:** Frontend library for building the user interface.
- **Vite:** Fast development server and build tool.
- **Tailwind CSS:** Utility-first CSS framework for styling.

## Getting Started

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repository or navigate to the project directory:
   ```bash
   cd country-explorer
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

### Running the App

Start the development server:
```bash
npm run dev
```
Open your browser and visit the local URL provided in the terminal (usually `http://localhost:5173`) to view the application.

## Project Structure

- `src/App.jsx`: Main application component handling state, API requests, and layout.
- `src/components/SearchBar.jsx`: Component for the search input.
- `src/components/CountryList.jsx`: Component rendering the list of filtered countries.
