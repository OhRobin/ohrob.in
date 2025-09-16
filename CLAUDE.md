# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with the CopyPasta demo website and personal site.

## Project Overview

This directory contains the CopyPasta demo website and personal website components:

1. **CopyPasta Demo Website** (`copypasta/`) - Marketing and demo website showcasing the CopyPasta macOS app
2. **Personal Website** (root files) - Robin's personal website at ohrob.in

## Repository Structure

```
ohrob.in/
├── CLAUDE.md              # This file - website development guidance
├── CNAME                  # GitHub Pages custom domain configuration
├── index.html             # Personal website homepage
├── privacy.html           # Privacy policy page
├── terms.html             # Terms of service page
└── copypasta/             # CopyPasta demo website
    ├── index.html         # Landing page with product overview
    ├── style.css          # Styling and responsive design
    ├── thanks.html        # Post-purchase confirmation page
    ├── README.md          # Website-specific documentation
    └── assets/            # Demo assets
        ├── CopyPasta_demo_final_final.gif  # Product demo animation
        └── tray_icon.png                   # App icon for website
```

## CopyPasta Demo Website (`copypasta/`)

### Website Features
- **Landing Page** (`index.html`): Product overview, features showcase, and purchase integration
- **Animated Demo** (`assets/CopyPasta_demo_final_final.gif`): Visual demonstration of app functionality
- **Purchase Integration**: LemonSqueezy payment processing with redirect to thank you page
- **Thank You Page** (`thanks.html`): Post-purchase confirmation and download instructions
- **Responsive Design** (`style.css`): Mobile and desktop optimized styling

### Key Components
- **Hero Section**: Eye-catching introduction with demo GIF
- **Features List**: Clear value propositions and app benefits
- **Purchase CTA**: Prominent buy button with LemonSqueezy integration
- **Privacy/Terms Links**: Legal compliance with proper footer links

### Development Workflow
- **Local Development**: Open `index.html` directly in browser for testing
- **Styling**: Edit `style.css` for visual changes
- **Content Updates**: Modify HTML files for copy changes
- **Asset Management**: Place images/videos in `assets/` directory

### Purchase Flow Integration
1. User clicks "Buy CopyPasta" button on landing page
2. Redirected to LemonSqueezy checkout with product ID
3. After successful purchase, redirected to `thanks.html`
4. Thank you page provides download link and setup instructions

## Personal Website (Root Files)

### Core Pages
- **Homepage** (`index.html`): Personal introduction and portfolio overview
- **Privacy Policy** (`privacy.html`): Privacy terms for CopyPasta and website
- **Terms of Service** (`terms.html`): Usage terms and legal information

### Hosting Configuration
- **GitHub Pages**: Hosted via GitHub Pages with custom domain
- **CNAME**: Custom domain configuration for ohrob.in
- **SSL/HTTPS**: Automatic GitHub Pages SSL certificate

## Development Guidelines

### Content Updates
- Keep messaging clear and focused on user benefits
- Maintain consistent branding across all pages
- Update demo assets when app features change
- Ensure legal pages stay current with app functionality

### Technical Considerations
- **Cross-browser Compatibility**: Test on major browsers (Safari, Chrome, Firefox)
- **Mobile Responsiveness**: Ensure proper display on all device sizes
- **Loading Performance**: Optimize images and minimize CSS/JS
- **SEO**: Maintain proper meta tags and structured content

### Asset Management
- **Images**: Optimize for web (compress, appropriate formats)
- **Demo GIF**: Keep file size reasonable while maintaining quality
- **Icons**: Use consistent iconography matching the macOS app

## Deployment

### GitHub Pages Setup
- Repository: `git@github.com:OhRobin/ohrob.in.git`
- Branch: `main` (auto-deploys on push)
- Custom Domain: `ohrob.in` (configured via CNAME)
- SSL: Automatic via GitHub Pages

### Content Updates Process
1. Make changes to HTML/CSS files locally
2. Test changes by opening files in browser
3. Commit and push to `main` branch
4. GitHub Pages automatically deploys changes
5. Verify live site at ohrob.in

## Integration with Main App

### Cross-References
- Website promotes the macOS app built in `../copypasta-app/`
- Download links point to LemonSqueezy distribution
- Demo content should match actual app functionality
- Legal pages cover both website and app usage

### Consistency Requirements
- Feature descriptions must match actual app capabilities
- Screenshots/demos should reflect current app version
- Pricing information must stay synchronized with LemonSqueezy
- Privacy policy must cover both website analytics and app data usage