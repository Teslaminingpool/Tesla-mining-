# Tesla Mining Network

A modern web application for cryptocurrency mining visualization and management with Tesla-inspired design.

## Features

- Real-time mining statistics dashboard
- Interactive crypto wallet management
- Flash BTC transaction capabilities
- Modern, responsive UI with Tesla branding
- Secure transaction processing

## Deployment

This project is built and ready for deployment. The compiled assets are located in the `assets/` directory.

### Quick Deploy

Deploy to Vercel:
```bash
vercel --prod
```

Or use any static hosting service by serving the root directory.

## File Structure

```
.
├── index.html          # Main HTML entry point
├── assets/             # Compiled JavaScript and CSS
│   ├── index-B08Tku8C.js
│   └── index-DM-CsTgw.css
├── tesla-hero.jpg      # Hero image
├── tesla-logo.png      # Logo asset
└── README.md          # This file
```

## Technologies Used

- React 19.2.3
- Modern JavaScript (ES2020+)
- CSS3 with custom styling
- Vite build system

## Local Development

To view the application locally, serve the root directory with any static file server:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## License

See [LICENSE](./LICENSE) file for details.

## Security Notice

This application handles cryptocurrency transactions. Always ensure you're using the latest version and follow security best practices when handling sensitive financial data.
