# Astrophotography Gallery Website

## Open the site
Open `index.html` in a browser.

## Replace the logo
In `index.html`, replace `YOUR LOGO` with your name or studio name.
You can also replace the circular `.brand-mark` in the header with an image:
```html
<img src="assets/your-logo.svg" alt="Your logo">
```

## Replace the background
Copy your chosen space image into the `assets` folder, then edit this line in `styles.css`:
```css
url("assets/space-background.svg")
```
For example:
```css
url("assets/my-background.jpg")
```
The 50px blur is already applied.

## Replace gallery photos
1. Put your image files in `assets/`.
2. Replace each image `src` in `index.html`.
3. Update `data-title`, `data-description`, and `data-image` on each `.gallery-card`.

## Replace gear images and descriptions
Replace the four gear SVG files or update the image paths in the Gear section.
Edit the equipment names and descriptions directly in `index.html`.

## Replace the portrait and story
Replace `assets/portrait-placeholder.svg` with your portrait.
Edit the About section text in `index.html`.

## Fonts
The site uses Orbitron and Space Grotesk from Google Fonts. If you want a fully offline version,
download and self-host appropriate font files or substitute system fonts in `styles.css`.
