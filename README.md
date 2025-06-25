# Movie App with ReactJS

A responsive web application built with React and Vite that allows users to browse, search, and manage a list of their favorite movies. The application fetches data from The Movie Database (TMDB) API and uses local storage to persist user favorites.

## ✨ Features

* **Browse Popular Movies**: View a list of the most popular movies on the homepage.
* **Search Functionality**: Search for movies by title.
* **Favorites System**: Add or remove movies from a personal favorites list.
* **Persistent State**: Favorites are saved in the browser's local storage.
* **Responsive Design**: A clean and modern UI that works on various screen sizes.
* **Routing**: Utilizes `react-router-dom` for seamless navigation between the Home and Favorites pages.

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

* Node.js (v18.0.0 or higher)
* npm (v8.0.0 or higher)
* A free API key from [The Movie Database (TMDB)](https://www.themoviedb.org/signup)

### Installation & Setup

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/rahil-shah/movie-app-with-reactjs.git](https://github.com/rahil-shah/movie-app-with-reactjs.git)
    cd movie-app-with-reactjs
    ```

2.  **Install NPM packages:**
    ```sh
    npm install
    ```

3.  **Configure API Key:**
    * Open the `src/services/api.js` file.
    * Replace the empty string for `API_KEY` with your TMDB API key.
    ```javascript
    // src/services/api.js
    const API_KEY = "YOUR_TMDB_API_KEY"; // <-- Add your key here
    ```

4.  **Run the development server:**
    ```sh
    npm run dev
    ```
    The application will be available at `http://localhost:5173`.

## 📂 Project Structure

The project follows a standard React application structure, organizing files by their function.