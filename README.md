# Weather Journal

Small fullstack exercise from the EGFWD nanodegree. You type a city, the app fetches the current weather from the OpenWeather API, saves the entry to a small Express server, and shows it on the page.

Nothing fancy, but it was the first time I connected a frontend to a backend I wrote myself, and that's exactly what it was for.

## Running it

```bash
git clone https://github.com/Ibrahim-Rezq/egfwd-weather-app.git
cd egfwd-weather-app
npm install
npm start
```

That starts the Express server. Then open `index.html` from the `website/` folder in your browser (or through a live server) and enter a city.

## How it's laid out

```
├── server/     # Express backend
├── website/    # frontend HTML, CSS, JS
└── package.json
```

## Stack

Vanilla JavaScript, HTML, and CSS on the front. Node and Express on the back. OpenWeather API for the data. No frameworks anywhere; that was the point.
