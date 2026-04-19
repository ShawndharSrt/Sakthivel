# Wedding Invitation Website - Sakthivel & Lalitha

A premium, modern, and responsive single-page wedding invitation website built with HTML and CSS. This project features a "Midnight Navy & Champagne Gold" theme, glassmorphism effects, a countdown timer, event details, and background music.

## Features

- **Interactive Welcome Gate**: A sophisticated entry screen that initializes the experience.
- **Premium UI**: Uses Glassmorphism, modern typography (Playfair Display & Outfit), and a rich color palette.
- **Countdown Timer**: Real-time countdown to the Muhurtham on May 20, 2026.
- **Event Details**: Beautifully styled cards for the Reception and Muhurtham with Font Awesome icons.
- **Venue Integration**: Direct links to Google Maps for both events.
- **Background Music**: Ambient wedding music that starts upon entry.
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop viewing.

## Project Structure

```
sakthivel/
├── index.html           # Main application file (HTML, CSS, JS)
├── vercel.json          # Vercel deployment configuration
├── music/
│   └── wedding-song.mp3 # Background music track
├── couple.png           # Hero and Couple section image
├── left.png             # Welcome gate decoration (left)
└── right.png            # Welcome gate decoration (right)
```

## Customization Instructions

To update the site for a different couple or date:

### 1. Update Names and Dates
- Search for `Sakthivel` and `Lalitha` in `index.html` and replace them.
- Update the date strings for the countdown (search for `targetDate` in the script section).

### 2. Change the Color Theme
The colors are defined in the `:root` section of the `<style>` tag:
```css
:root {
  --primary: #0f172a;       /* Background Color */
  --secondary: #c5a059;     /* Gold Accent Color */
  /* ... */
}
```

### 3. Replace Images
- `couple.png`: The main photo of the couple.
- `left.png` & `right.png`: Corner floral/mandala decorations.

### 4. Update Venue Links
- Replace the `href` in the "View on Maps" buttons with your specific Google Maps share links.

## Deployment

This project is ready for deployment on [Vercel](https://vercel.com).
1. Connect your GitHub repository to Vercel.
2. Deploy with default settings.
