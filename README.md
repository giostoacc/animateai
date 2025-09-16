# AnimateAI Landing Page

A beautiful, modern landing page for AnimateAI - an AI service that transforms images into animated videos.

## Features

- 🎨 **Modern Design**: Clean, sophisticated interface with Lovable-inspired color scheme
- ✨ **Animated Background**: Continuous particle animation using anime.js
- 📱 **Responsive**: Works perfectly on desktop and mobile devices
- 🖼️ **Image Upload**: Drag-and-drop interface for image uploads
- 💬 **Chat Interface**: Interactive chat for user instructions
- 🎭 **Glassmorphism Effects**: Modern UI with backdrop blur and transparency

## Color Scheme

The landing page uses a beautiful gradient color palette inspired by Lovable:
- Deep indigo to purple to vibrant orange-pink gradient
- Dark background with glassmorphism effects
- Pink and blue accent colors

## Background Animation

The page features a sophisticated particle animation system that:
- Creates 80 floating particles across the entire screen
- Uses infinite forward movement (no looping back)
- Particles move in random directions continuously
- Colors match the Lovable-inspired palette (pink to purple)
- Smooth, non-distracting movement

## Setup Instructions

### Option 1: Simple HTTP Server (Recommended)

1. **Clone the repository:**
   ```bash
   git clone https://github.com/giostoacc/animateai.git
   cd animateai
   ```

2. **Start a local server:**
   ```bash
   # Using Python 3
   python3 -m http.server 8000
   
   # Or using Python 2
   python -m SimpleHTTPServer 8000
   
   # Or using Node.js (if you have it installed)
   npx serve .
   ```

3. **Open your browser:**
   Navigate to `http://localhost:8000`

### Option 2: Direct File Opening

Simply open `index.html` in your web browser, though some features may not work due to CORS restrictions.

## File Structure

```
animateai/
├── index.html          # Main landing page
├── anime.esm.js        # Anime.js library for animations
└── README.md           # This file
```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with gradients, glassmorphism, and animations
- **JavaScript (ES6)**: Interactive functionality and file handling
- **Anime.js**: Smooth particle animations and transitions

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Customization

The landing page is designed to be easily customizable:

- **Colors**: Modify CSS variables in the `:root` section
- **Animation**: Adjust particle count and movement in the JavaScript
- **Content**: Update text and branding in the HTML
- **Layout**: Modify the CSS grid and flexbox layouts

## License

This project is open source and available under the MIT License.

## Contributing

Feel free to submit issues and enhancement requests!

---

**AnimateAI** - Transform your images into stunning animated videos with the power of AI.
