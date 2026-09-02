# TykaasMovie 🎬

TykaasMovie is a modern movie recommendation web app with an elegant brown + blue visual identity.

## Catalog
- 100 movie titles across Western, K-Drama, Anime, Romance, Comedy, Action, Drama, Fantasy, and Mystery.
- 20 titles appear at first; use Load More to reveal more.

## Features
- Search movies
- Genre/category filters
- Western, K-Drama, Anime, Romance, Action, Comedy
- Random movie recommendation
- Movie detail modal
- Favorites saved in localStorage
- Official/legal viewing search button
- Responsive design for desktop and mobile

## How to run
1. Extract the ZIP.
2. Open `index.html` in a browser.
3. Internet connection is recommended because the project uses Google Fonts and remote poster images.

## Important
The "Watch / Official page" button currently opens JustWatch, a legal streaming availability guide. It does not host movies itself. You can replace each `watch` URL in `script.js` with the official streaming page you are allowed to use.

## Customize
Edit the `movies` array in `script.js` to add or replace titles, descriptions, poster URLs, genres, and official viewing links.

POSTER UPDATE
The 100 movie entries now automatically load real movie-related poster/page images from Wikipedia/Wikimedia's public MediaWiki PageImages API when the site is opened online. Images are cached in the browser so repeat visits load faster. If a title has no suitable Wikipedia page image, the original fallback image remains.
