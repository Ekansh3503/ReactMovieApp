**React Movie App**

This is a simple React application that allows users to search for movies using the OMDB API, add them to their favourites list, and view their favourite movies. The application utilizes React hooks for state management and Bootstrap for styling.

### Features:
- Search for movies using the OMDB API.
- Add movies to favourites.
- Remove movies from favourites.
- Favourites list persists across sessions using browser's local storage.

### Installation:
1. Clone the repository:
   ```
   git clone https://github.com/Ekansh3503/react-movie-app.git
   ```
2. Navigate to the project directory:
   ```
   cd react-movie-app
   ```
3. Install dependencies:
   ```
   npm install
   ```
4. Start the development server:
   ```
   npm start
   ```
   This will run the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### Usage:
1. Enter a movie title in the search box and press Enter or click on the search button.
2. The application will fetch movies matching the search query from the OMDB API and display them.
3. Click on the heart icon to add a movie to your favourites.
4. To view your favourite movies, scroll down to the "Favourites" section.
5. To remove a movie from your favourites, click on the heart icon again.

### Technologies Used:
- React.js
- Bootstrap

### Folder Structure:
```
react-movie-app/
│
├── public/
│   ├── index.html
│   └── ...
│
├── src/
│   ├── components/
│   │   ├── AddFavourites.js
│   │   ├── Movie.js
│   │   ├── MovieList.js
│   │   ├── MovieListHeading.js
│   │   ├── RemoveFavourites.js
│   │   ├── SearchBox.js
│   │   └── ...
│   ├── App.css
│   ├── App.js
│   ├── index.css
│   ├── index.js
│   └── ...
│
├── .gitignore
├── package-lock.json
├── package.json
└── README.md
```

### License:
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### Author:
[Your Name]

Feel free to contribute to the project or report any issues you encounter!
