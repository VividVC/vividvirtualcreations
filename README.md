# Vivid Virtual Creations Website

A modern, responsive website for Vivid Virtual Creations showcasing digital services and creative solutions.

## 🌐 Live Website

**Production URL**: https://vividvirtualcreations-e1rrqqrqu-zac-sheets-projects.vercel.app

## Features

- **Modern Design**: Clean, professional design with gradient backgrounds and smooth animations
- **Responsive Layout**: Fully responsive design that works on all devices
- **Interactive Elements**: Smooth scrolling, hover effects, and animated counters
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Performance Optimized**: Fast loading with optimized assets

## Technologies Used

- HTML5
- CSS3 (with modern features like Grid, Flexbox, and CSS Variables)
- Vanilla JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Inter)

## File Structure

```
/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── vercel.json         # Vercel deployment configuration
└── README.md          # This file
```

## Local Development

1. Clone or download the project files
2. Open `index.html` in your web browser
3. The website should load with all functionality working

## Deployment

### Vercel Deployment (Current)

The website is deployed on Vercel for optimal performance and global CDN distribution.

**Deployment Commands:**
```bash
# Deploy to Vercel
vercel --prod

# List deployments
vercel ls

# View deployment details
vercel inspect
```

### GitHub Pages Deployment (Alternative)

#### Prerequisites

1. Install GitHub CLI if you haven't already:
   ```bash
   # Windows (using winget)
   winget install GitHub.cli
   
   # Or download from: https://cli.github.com/
   ```

2. Authenticate with GitHub:
   ```bash
   gh auth login
   ```

#### Deployment Steps

1. **Initialize Git Repository** (if not already done):
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Vivid Virtual Creations website"
   ```

2. **Create GitHub Repository**:
   ```bash
   gh repo create vividvirtualcreations --public --source=. --remote=origin --push
   ```

3. **Enable GitHub Pages**:
   ```bash
   gh repo edit vividvirtualcreations --add-topic pages
   ```

4. **Configure GitHub Pages**:
   - Go to your repository on GitHub
   - Navigate to Settings > Pages
   - Set Source to "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click "Save"

5. **Your website will be available at**:
   ```
   https://[your-username].github.io/vividvirtualcreations
   ```

### Custom Domain Setup

If you own the domain `vividvirtualcreations.com`:

#### For Vercel:
1. Go to your Vercel dashboard
2. Select the project
3. Go to Settings > Domains
4. Add your custom domain: `vividvirtualcreations.com`
5. Configure DNS records as instructed by Vercel

#### For GitHub Pages:
1. **Add Custom Domain**:
   - In your repository Settings > Pages
   - Add your custom domain: `vividvirtualcreations.com`
   - Check "Enforce HTTPS"

2. **Configure DNS**:
   - Add a CNAME record pointing to `[your-username].github.io`
   - Or add A records pointing to GitHub Pages IP addresses

3. **Create CNAME file** (optional):
   ```bash
   echo "vividvirtualcreations.com" > CNAME
   git add CNAME
   git commit -m "Add custom domain"
   git push
   ```

## Customization

### Colors
The website uses a modern color scheme with gradients. You can customize colors in `styles.css`:

- Primary gradient: `#667eea` to `#764ba2`
- Accent gradient: `#f093fb` to `#f5576c`
- Primary color: `#6366f1`

### Content
- Update the content in `index.html` to match your business
- Replace placeholder text and contact information
- Add your own portfolio items and services

### Images
- Replace placeholder elements with actual images
- Update the `image-placeholder` divs with your own images

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

The website is optimized for performance with:
- Minimal external dependencies
- Optimized CSS and JavaScript
- Responsive images and icons
- Smooth animations using CSS transforms
- Global CDN distribution via Vercel

## License

This project is open source and available under the MIT License.

## Support

For questions or support, please contact the development team or create an issue in the GitHub repository.
