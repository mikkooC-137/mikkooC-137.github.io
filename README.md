# Greenland Status Checker

A fun website that checks Wikipedia to determine if Greenland is part of the USA or Denmark, with humorous status messages and donation buttons.

## Setup Instructions

### Adding Flag Images

To display proper flag images, download and add these files to the same folder as `index.html`:

1. **usa-flag.png** - USA flag image
   - Recommended size: 500-800px width
   - Suggested source: Search for "USA flag PNG transparent" or download from:
     - https://www.flaticon.com/free-icon/united-states_206626
     - https://commons.wikimedia.org/wiki/File:Flag_of_the_United_States.svg

2. **denmark-flag.png** - Denmark flag image
   - Recommended size: 500-800px width
   - Suggested source: Search for "Denmark flag PNG transparent" or download from:
     - https://www.flaticon.com/free-icon/denmark_197565
     - https://commons.wikimedia.org/wiki/File:Flag_of_Denmark.svg

### Optional: Better Greenland Image

You can also replace the SVG Greenland map with a real image:

3. **greenland-map.png** - Greenland map/photo (optional)
   - Suggested sources:
     - https://commons.wikimedia.org/wiki/File:Greenland_location_map.svg
     - Search for "Greenland map PNG"

If you don't add these images, the site will use fallback SVG graphics (which still look good!).

## Setting Up PayPal Payments

To enable real PayPal donations:

1. Create PayPal.me links for your accounts
2. Edit `index.html` around line 447-450
3. Replace the placeholder URLs:
   - `'https://www.paypal.com/paypalme/YourPayPalUSA'`
   - `'https://www.paypal.com/paypalme/YourPayPalDenmark'`
4. Uncomment line 461: `// window.open(paypalLinks[side], '_blank');`

## Features

- ✅ Real-time Wikipedia scraping
- ✅ 10 funny rotating status messages
- ✅ Animated flag overlay on Greenland map
- ✅ PayPal donation buttons for both sides
- ✅ Responsive design
- ✅ Lightweight (only uses jQuery)

## Running the Site

Simply open `index.html` in any modern web browser. No server required!

## File Structure

```
groenland/
├── index.html          (main website file)
├── usa-flag.png        (add this - USA flag image)
├── denmark-flag.png    (add this - Denmark flag image)
└── README.md           (this file)
```

## Browser Compatibility

Works in all modern browsers:
- Chrome/Edge
- Firefox
- Safari
- Opera

Enjoy the website! 🌍
