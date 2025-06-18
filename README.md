# The Quote Card (Express) - A Code:You Project

A simple web app that displays a quote card with a random Unsplash background image. The backend is built with Express.js and serves both the static frontend and an API endpoint to fetch random images.

## Features

- Displays a quote and author in a styled card.
- Dynamically fetches a random background image from Unsplash via a backend API.
- Responsive and modern CSS design.
- Easily extensible for more quotes or features.

## Getting Started

1. **Install dependencies:**
   ```
   npm install
   ```

2. **Set up environment variables:**
   - Create a `.env` file in the root directory.
   - Add your Unsplash API access key:
     ```
     UNSPLASH_ACCESS_KEY=your_access_key_here
     ```

3. **Run the server:**
   ```
   npm run dev
   ```
   The app will be available at http://localhost:8080.

## Project Structure

- `server.js` — Express server and API endpoint.
- `public/` — Static frontend (HTML, CSS, JS, images).
- `public/js/index.js` — Fetches random image and updates the background.
- `public/css/` — Styles and CSS reset.


