# Random Airport Picker

Small browser app that suggests a random airport by querying Kiwi's location API.

## What It Does

- Generates a random 3-letter code
- Queries airport data from the API
- Displays airport code, name, and city/country

## Run Locally

This is a static HTML/CSS/JS project.

- Open `index.html` directly in your browser, or
- Serve the folder with a static server

Example:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Project Structure

- `index.html` - page markup
- `style.css` - styles
- `index.js` - random code generation + API request logic
