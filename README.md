# JReader - Privacy Policy and Support Pages

This repository contains the privacy policy and support pages for the JReader iOS app.

## Pages

- **Privacy Policy**: [privacy.html](privacy.html) - Details about data collection and privacy practices
- **Support**: [support.html](support.html) - Help, troubleshooting, and contact information  
- **Home**: [index.html](index.html) - Main landing page with app information

## GitHub Pages Setup

1. Go to your repository Settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click "Save"

Your site will be available at: `https://yourusername.github.io/repositoryname`

## URLs for App Store

Once GitHub Pages is set up, use these URLs in your App Store Connect listing:

- **Privacy Policy URL**: `https://yourusername.github.io/repositoryname/privacy.html`
- **Support URL**: `https://yourusername.github.io/repositoryname/support.html`

## Local Development

To preview the site locally:

```bash
# Using Python's built-in server
python3 -m http.server 8000

# Then visit http://localhost:8000 in your browser
```

## File Structure

```
├── index.html          # Main landing page
├── privacy.html        # Privacy policy page  
├── support.html        # Support and help page
├── styles.css          # Shared CSS styles
├── assets/
│   └── images/         # App icons and favicon
│       ├── favicon.png
│       ├── favicon-16.png
│       ├── favicon-32.png
│       ├── icon-120.png
│       └── icon-180.png
└── README.md          # This file
```