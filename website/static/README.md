# Static HTML Version

This is a standalone HTML/CSS version of the donation landing page that works with Python's http.server (no build tools required).

## How to Run

From the website directory:

```bash
cd static
python3.12 -m http.server 8080
```

Then open your browser to: `http://localhost:8080`

## Files

- `index.html` - Main HTML structure with all content
- `styles.css` - All styling (responsive, mobile-first)

This version includes all the same features as the React version:
- Organization logo placeholder
- Hero banner with title overlay
- Donate Now CTA buttons
- Mission, campaign, and impact sections
- Testimonials (3 cards)
- Fully responsive design
- Accessibility features

The 404 error for favicon.ico is normal and won't affect functionality.
