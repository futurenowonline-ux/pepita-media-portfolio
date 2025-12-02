# Pepita Media Portfolio Website

This is a single-page portfolio website for "Pepita Media", a photography brand based in Durban, South Africa.

## Features

- **Responsive Design**: Mobile-first approach ensuring the site looks good on all devices.
- **Modern Aesthetics**: Clean, elegant design with a focus on typography and imagery.
- **Interactive Elements**: Smooth scrolling, mobile navigation menu, and hover effects.
- **Semantic HTML5**: Accessible and SEO-friendly structure.
- **Vanilla CSS & JS**: No external frameworks, ensuring lightweight and fast performance.

## Customization

### Colors

You can easily change the color scheme by editing the CSS variables in `style.css` under the `:root` selector:

```css
:root {
    --bg-color: #F9F7F2; /* Background Color */
    --text-color: #333333; /* Text Color */
    --accent-color: #E29578; /* Primary Accent Color */
    --accent-hover: #D4A373; /* Hover State Color */
    /* ... */
}
```

### Typography

The site uses Google Fonts. To change fonts, update the `<link>` tag in `index.html` and the font variables in `style.css`:

```css
:root {
    --font-heading: 'Playfair Display', serif;
    --font-body: 'Lato', sans-serif;
}
```

### Images

The site currently uses placeholder images from `via.placeholder.com`. To replace them with real images:

1.  Add your image files to an `images` folder (you'll need to create this).
2.  Update the `src` attributes in `index.html` to point to your local files.
3.  Update the `background-image` URL in `style.css` for the hero section.

## How to Run

Simply open `index.html` in any modern web browser.
