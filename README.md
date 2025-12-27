# PhyAVBench Project Page

This is the project page for PhyAVBench, a benchmark for physical audio-visual understanding.

## Structure

- `index.html` - Main HTML page
- `styles.css` - Styling for the page
- `script.js` - JavaScript for interactive charts
- `README.md` - This file

## Setup

1. Open `index.html` in a web browser
2. For full functionality, serve the page through a local web server (e.g., `python -m http.server` or `npx serve`)

## Customization

### Update Content

1. **Title and Authors**: Edit the header section in `index.html`
2. **Abstract**: Modify the abstract text in the abstract section
3. **Statistics**: Update the numbers in the stats-grid section
4. **Charts**: Modify the data in `script.js` for category and material distributions
5. **Videos**: Replace the video sources in the video-grid section with your actual video files

### Add Videos

1. Create a `videos/` directory
2. Place your video files in the directory
3. Update the video source paths in `index.html`
4. Optionally add poster images for video thumbnails

### Styling

Modify `styles.css` to customize colors, fonts, and layout to match your preferences.

## Dependencies

- Chart.js (loaded via CDN) - for data visualization charts

## Browser Support

Modern browsers (Chrome, Firefox, Safari, Edge) with HTML5 video support.

