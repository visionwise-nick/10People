# 10People Official Website

The official website for **10People** — a minimalist "safety check" and "mind connection" app.

## Product Information

- **Product Name**: 10People
- **Slogan**: The world is loud, I just want to hear your heartbeat.
- **Core Value**: Minimalist "safety check" and "mind connection"

## Website Structure

```
website/
├── index.html          # Homepage
├── styles.css          # Stylesheets
├── script.js           # JavaScript functionality
├── assets/
│   └── icon/
│       └── app_icon.png # App icon
└── README.md           # Documentation
```

## Core Features

### Homepage (index.html)
- Responsive design for mobile and desktop
- Product introduction and core features
- Core interactions: Daily light up, Widget 2.0, The Nudge
- Viral growth: Only 10 "tickets" for scarcity marketing
- Download links for App Store and Google Play
- Modern UI with smooth animations

### Core Philosophy
1. **The 10 Rings**: Only 10 spots for the most important people
2. **Daily Light Up**: Tap to glow, long press to share a short status (under 20 characters)
3. **Widget 2.0: The Window**: View your circle without opening the app
4. **The Nudge**: The only communication method — no chat boxes
5. **Anti-Social by Design**: No history, no precise timestamps, resets at midnight
6. **10 Rare Tickets**: Invite-only connections through unique links

## Technical Features

- **Responsive Design**: Adapts to all screen sizes
- **Modern CSS**: Flexbox and Grid layouts
- **Smooth Animations**: CSS transitions and JavaScript interactions
- **SEO Optimized**: Semantic HTML and meta tags
- **Performance**: Optimized images and code

## Deployment to GitHub Pages

### Method 1: Using GitHub Pages Settings (Recommended)

1. Push the website folder to your GitHub repository
2. Go to repository Settings → Pages
3. Under "Build and deployment", select:
   - Source: "Deploy from a branch"
   - Branch: `main`
   - Folder: `/website` (or root if you move contents to root)
4. Click "Save"
5. Your site will be live at: `https://visionwise-nick.github.io/10People/`

### Method 2: Using GitHub Actions (Advanced)

Create `.github/workflows/deploy.yml` for automatic deployment on push.

### Method 3: Using Subtree Push

```bash
# Push only the website folder to gh-pages branch
git subtree push --prefix website origin gh-pages
```

## Local Development

1. Clone the repository
2. Navigate to the website directory
3. Start a local server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js (with http-server installed)
   npx http-server -p 8000
   ```
4. Open `http://localhost:8000` in your browser

## Customization

### Update Contact Information
Update contact details in:
- `index.html` - Footer section

### Update Download Links
Modify the App Store and Google Play links in the Download section of `index.html`.

### Change Colors and Styling
Edit `styles.css` to customize the color scheme and design elements.

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

© 2026 10People. All rights reserved.
