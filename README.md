# Donation Landing Page

A responsive React-based landing page skeleton for a non-profit organization's 1-month fundraising campaign.

## Features

✅ **All Required Components:**
- Organization logo placeholder (top center)
- Hero image with semi-transparent banner
- Title overlay on hero section
- Multiple text blocks for mission, campaign info, and impact
- Testimonials section with 3 placeholder cards
- Prominent "Donate Now" CTA buttons

✅ **Responsive Design:**
- Mobile-first approach
- Optimized for mobile, tablet, and desktop devices
- Breakpoints at 480px and 768px

✅ **Accessibility:**
- Semantic HTML structure
- ARIA labels for buttons
- Keyboard navigation support
- Focus indicators
- Reduced motion support
- High contrast mode support

✅ **Clean & Simple Design:**
- Modern gradient styling
- Card-based layouts
- Hover effects and transitions
- Professional typography

## Project Structure

```
website/
├── public/
│   └── index.html          # HTML entry point
├── src/
│   ├── App.js              # Main React component
│   ├── App.css             # Component styling
│   ├── index.js            # React DOM renderer
│   └── index.css           # Global styles
└── package.json            # Dependencies
```

## Installation

1. Navigate to the website directory:
```bash
cd website
```

2. Install dependencies:
```bash
npm install
```

## Running the Application

Start the development server:
```bash
npm start
```

The application will open in your browser at `http://localhost:3000`

## Building for Production

Create an optimized production build:
```bash
npm run build
```

The build files will be in the `build/` directory.

## Customization

This is a skeleton/schematic with placeholders. To customize:

1. **Logo**: Replace `[Organization Logo]` in the header with actual logo image
2. **Hero Image**: Add background image to `.hero-section` CSS
3. **Content**: Replace all `[Placeholder text]` with actual content
4. **Links**: Update `href="#donate"` to actual donation URL
5. **Colors**: Modify the gradient colors in App.css to match brand
6. **Testimonials**: Add real testimonials and author names

## Technologies Used

- React 18.2.0
- JavaScript (ES6+)
- CSS3 with Flexbox and Grid
- HTML5

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Next Steps

1. Add actual organization logo and hero image
2. Replace placeholder content with real text
3. Integrate with donation payment platform
4. Add form validation if needed
5. Connect analytics tracking
6. Optimize images and assets
7. Deploy to hosting platform

## License

This project is created for a non-profit organization's fundraising campaign.
