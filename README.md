# Jimmy's Visual Stock Manager

A visual, interactive stock management tool for site maps. Built for easy, intuitive management of stock locations, quantities, and financials on a real-world site map.

## Features
- Upload your own site map image
- Add, drag, and delete stock pins for products
- Categorize products (Wet Press, Block Plant, Brought In)
- Live search and filter for pins and products
- Top products and financials panels
- Editable product costs (with normalization for matching)
- Recent stock movements log
- Data persistence via localStorage
- Export/import data as JSON
- Modern, responsive UI

## Setup
1. Clone or download this repository.
2. Place your site map image as `sitemap.png` in the project folder.
3. Open `index.html` in your browser to use the app.
4. (Optional) Edit product costs in `financials.html`.

## Usage
- **Upload Site Map:** Click the upload button to set your background image.
- **Add Pin Mode:** Click to enable, then click on the map to drop a pin.
- **Drag Pins:** Click and drag any pin to reposition it. Position is saved automatically.
- **Delete Pins:** Click a pin, then click the 🗑 button in the tooltip.
- **Edit Costs:** Go to the Financials page to set or update product costs. All cost lookups are case/space-insensitive.
- **Search/Filter:** Use the search box and category filter in the header to find pins/products instantly.
- **Export Data:** Download your current stock data as JSON for backup or sharing.

## Requirements
- Modern web browser (Chrome, Edge, Firefox, Safari)
- No server or backend required (all data is local)

## File List
- `index.html` — Main app UI and logic
- `financials.html` — Product cost editor
- `sitemap.png` — Your site map image (replace with your own)

## Credits
- Built by Jimmy (Crawford1982)
- Lightning icon favicon by SVG
- UI inspired by modern dashboard best practices

## License
MIT (or specify your own) 