# GEMINI.md

## Project Overview

This project is a simple, static photo gallery website. It displays a grid of images from the `assets/` directory on a single page. The layout and styling are handled with basic HTML and CSS. The title of the page is "Maialona Mia".

## Key Files

*   `index.html`: The main HTML file that defines the structure of the web page. It contains the header, the image grid, and the footer.
*   `index.css`: The stylesheet for the project. It defines the layout (including the responsive image grid), background, and fonts.
*   `background.png`: The background image for the website.
*   `assets/`: This directory contains the image files displayed in the gallery.

## Building and Running

This is a static website, so there is no build process.

To view the website, simply open the `index.html` file in a web browser.

For local development, it's recommended to use a simple local web server to avoid potential issues with file paths or future JavaScript additions (CORS). You can start one easily with Python:

```bash
# For Python 3
python -m http.server
```

Then, open your web browser and navigate to `http://localhost:8000`.

## Development Conventions

*   The image gallery is hardcoded to load images named from `1.JPG` to `18.JPG`. To add or change images, you must update the filenames in the `assets` directory and potentially modify the `index.html` file if you change the naming scheme or the number of images.
*   Styling is managed in a single `index.css` file.
