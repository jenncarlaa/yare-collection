# Yare Collection

A bilingual (English / Bahasa Indonesia) catalogue website for **Yare Collection**, a handcrafted pearl and gemstone jewelry brand from Indonesia. Visitors browse the pieces, read about each stone, and order directly through WhatsApp.

**Live site:** https://www.yarecollection.com

## Features

- Product catalogue by category (necklaces, bracelets, sets, brooches) with a detail sheet for each piece
- Stone guide: every stone has its own description, and pieces can be filtered by wellness intention (Calm, Protection, Focus and more)
- English and Bahasa Indonesia, switchable on the page
- Prices in rupiah or US dollars, with the rupiah amount converted from the dollar price
- Wishlist ("Save") for pieces the visitor likes
- Order buttons that open WhatsApp with the piece name already filled in
- Responsive layout for phone and desktop

## Tech

Plain HTML, CSS and vanilla JavaScript in a single `index.html`. No framework and no build step. The product data lives in the `ROWS` array in the script, so adding a piece means adding one row plus its photos.

## Run it locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Structure

```
index.html   the whole site (markup, styles, script, product data)
img/         product, collection and brand photos
```

Photos for the newest pieces (No. 49 onward) are loaded from the Wix media CDN, so those need an internet connection.

## Credits and license

Design and code: built for Yare Collection.
Product photos, the logo and the brand name belong to Yare Collection. All rights reserved. This repository is shared as a portfolio piece, please do not reuse the photos or branding.
