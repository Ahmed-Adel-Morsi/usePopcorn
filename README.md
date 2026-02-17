# usePopcorn

A React movie search and watchlist application that lets users discover films via the OMDb API, inspect details, rate movies, and maintain a persistent watched list in local storage.

## Live Demo

Deployed at: **https://ahmed-adel-morsi.github.io/usePopcorn**

## Features

- Search movies with live API results (minimum 3 characters).
- View detailed movie information (plot, cast, director, runtime, genre, release date, IMDb rating).
- Rate movies with a reusable star rating component.
- Add rated movies to a watched list.
- Remove movies from the watched list.
- Persist watched list data in `localStorage`.
- Display watched-list analytics:
  - Total watched movies
  - Average IMDb rating
  - Average user rating
  - Average runtime
- Keyboard shortcuts:
  - `Enter` focuses the search input and clears current query.
  - `Escape` closes selected movie details.

## Tech Stack

- React (Create React App)
- JavaScript (ES6+)
- Custom React hooks
- CSS
- OMDb API
- gh-pages (deployment)

## Project Structure

```text
src/
	App.js                # Main UI and app flow
	StarRating.js         # Reusable rating component
	useKey.js             # Keyboard shortcut hook
	useLocalStorage.js    # Local storage persistence hook
	useMovies.js          # Movie fetching hook with abort handling
	index.css             # App styling
	index.js              # React entry point
```

## Getting Started

### 1) Install dependencies

```bash
npm install
```

### 2) Run in development

```bash
npm start
```

Open `http://localhost:3000` in your browser.

## Available Scripts

- `npm start` — Runs the app in development mode.
- `npm test` — Launches the test runner.
- `npm run build` — Builds the app for production.
- `npm run deploy` — Deploys the production build to GitHub Pages.

## API

This app consumes data from the [OMDb API](https://www.omdbapi.com/).

## Credits

This project is inspired by the React course by **Jonas Schmedtmann** and was built as part of hands-on learning and practice.

## License

This project is for educational purposes.
