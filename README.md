# Movie Search App 🎬

A responsive web application that helps users discover movies using the TMDB API, with trending movie tracking powered by Appwrite.

![App Screenshot](./screenshot.png) <!-- Add a screenshot later -->

## Features ✨

- 🔍 Search movies from TMDB database
- 🚀 Discover popular movies
- 📊 Trending movies based on search history
- ⚡ Debounced search for better performance
- 📱 Fully responsive design

## Technologies Used 🛠️

- **Frontend**: 
  - React.js
  - Vite (for fast development)
  - Tailwind CSS (for styling)
  
- **Backend Services**:
  - TMDB API (for movie data)
  - Appwrite (for tracking trending searches)

## Installation & Setup 🚀

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- TMDB API key
- Appwrite project setup

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/VikHyatKumar/react-movie-app.git
   cd movie-search-app

2. Install Dependencies: 
   ```bash
   npm install
# or
   yarn install

3. Create a .env file in the root directory with your API keys:

VITE_TMDB_API_KEY=your_tmdb_api_key_here
VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
VITE_APPWRITE_DATABASE_ID=your_appwrite_db_id
VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id

4. Start the development server:
   ```bash
   npm run dev
# or
   yarn dev

5. Open your browser at http://localhost:5173   