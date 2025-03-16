# Cinemate: Movie Discovery App

## Overview 🎬

Welcome to **Cinemate**, your go-to movie discovery application! Powered by The Movie Database (TMDb) API, Cinemate allows you to explore movies, check ratings, view details, and search for your favorite films seamlessly.

## Features ✨

- **Dynamic Movie Listings**: Fetch movies dynamically from TMDb API.
- **Search Functionality**: Find movies using keywords.
- **Detailed Movie Pages**: View comprehensive details of each movie.
- **Dark Mode Support**: Toggle between light and dark mode.
- **Smooth Navigation**: Implemented with React Router.
- **Scroll to Top**: Auto scrolls to the top when navigating between pages.
- **Lazy Loading**: Efficient loading with optimized API calls.
- **404 Error Page**: Custom error page for unmatched routes.
- **Responsive UI**: Mobile-first design with TailwindCSS.

## Built With 🛠️

### Technologies Used:

- React.js ⚛️
- React Router 🚏
- TailwindCSS 🎨
- TMDb API 🎬
- JavaScript (ES6+)

### Tools & Libraries:

- **State Management**: useState, useEffect Hooks
- **API Fetching**: Fetch API
- **Version Control**: Git & GitHub
- **Routing**: React Router DOM

## Installation 💻

### 1️⃣ Clone the Repository:

```bash
$ git clone https://github.com/UrstrulyBhavana/Cinemate.git
$ cd Cinemate
```

### 2️⃣ Install Dependencies:

```bash
$ npm install
```

### 3️⃣ Set Up API Key:

- Create a `.env` file in the root directory.
- Add your TMDb API key:

```bash
REACT_APP_API_KEY=your_tmdb_api_key_here
```

### 4️⃣ Start the Development Server:

```bash
$ npm start
```

### 5️⃣ Build for Production:

```bash
$ npm run build
```

## API References 🔗

Cinemate fetches data from [The Movie Database (TMDb)](https://www.themoviedb.org/) API:

- **Base URL**: `https://api.themoviedb.org/3`
- **API Key**: Store in `.env` as `REACT_APP_API_KEY`

### API Endpoints:

| Feature            | Endpoint                           |
| ------------------ | ---------------------------------- |
| **Now Playing**    | `/movie/now_playing`               |
| **Popular Movies** | `/movie/popular`                   |
| **Top Rated**      | `/movie/top_rated`                 |
| **Upcoming**       | `/movie/upcoming`                  |
| **Search**         | `/search/movie?query={movie_name}` |
| **Movie Details**  | `/movie/{movie_id}`                |

## Folder Structure 📂

```
Cinemate
├── src
│   ├── components
│   │   ├── Header.js
│   │   ├── Footer.js
│   │   ├── Card.js
│   │   ├── Button.js
│   │   ├── ScrollToTop.js
│   ├── hooks
│   │   ├── useFetch.js
│   │   ├── useTitle.js
│   ├── pages
│   │   ├── MovieList.js
│   │   ├── MovieDetail.js
│   │   ├── Search.js
│   │   ├── PageNotFound.js
│   ├── routes
│   │   ├── AllRoutes.js
│   ├── assets (Images and icons)
│   ├── App.js
│   ├── index.js
│   ├── index.css
│   ├── tailwind.config.js
│   ├── .env (API Key configuration)
│   ├── package.json
│   ├── README.md
```

## Functionalities 🎥

1. **Movie Listings**:

   - Displays **Now Playing**, **Popular**, **Top Rated**, and **Upcoming** movies.
   - Uses `useFetch` custom hook for API calls.
   - Lazy loads movie lists for better performance.

2. **Movie Search**:

   - Search for movies using the **Search Bar**.
   - Dynamically fetches results from TMDb API.
   - Highlights relevant movie titles based on the query.

3. **Movie Details Page**:

   - Displays title, overview, rating, genre, runtime, release date, budget, revenue, and IMDb link.
   - Optimized UI with poster image and metadata.

4. **Dark Mode**:

   - Toggles between **light and dark themes**.
   - User preference is stored in `localStorage`.

5. **Navigation & Routing**:

   - **React Router** for smooth navigation.
   - **404 Page** for invalid URLs.
   - **Scroll-to-Top** feature for seamless navigation.

6. **Responsive UI**:

   - Styled using **TailwindCSS**.
   - Mobile-first layout with grid-based movie listings.

## Future Enhancements 🚀

- ✅ Add **User Authentication** (Login/Signup).
- ✅ Implement **Favorites & Watchlist** feature.
- ✅ Improve **Search Suggestions & Auto-Complete**.
- ✅ Add **Movie Trailers & Cast Information**.
- ✅ Optimize API calls using **React Query** or **Redux Toolkit**.

## Contributing 🤝

We welcome contributions! 🚀 If you’d like to contribute:

1. **Fork** this repository.
2. Create a **new branch** (`feature/new-feature`).
3. **Commit** your changes.
4. **Push** to your fork.
5. Open a **Pull Request**.

## Contact 📧

- **Developer**: Linga Bhavana
- **GitHub**: [UrstrulyBhavana](https://github.com/UrstrulyBhavana)
- **Email**: [urstrulybhavana1432@gmail.com](mailto\:urstrulybhavana1432@gmail.com)

## License 📄

This project is licensed under the **MIT License**
