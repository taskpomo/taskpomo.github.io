# TaskPomo Website

This is the official website for TaskPomo app.

## Structure

```
website/
├── index.html          # Homepage
├── privacy/
│   └── index.html      # Privacy Policy
├── terms/
│   └── index.html      # Terms of Service
├── contact/
│   └── index.html      # Contact Page
├── icon.png            # Favicon (1024x1024)
├── app-preview.png     # App screenshot for homepage
└── og-image-source.html # Source for social media image
```

## Deploy

### Option 1: Netlify (Recommended)
1. Create account at netlify.com
2. Drag and drop the `website` folder
3. Set custom domain to taskpomo.com

### Option 2: Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in website directory
3. Follow prompts

### Option 3: GitHub Pages
1. Create new repo: `taskpomo-website`
2. Push website contents
3. Enable GitHub Pages in settings

## Image Generation

To create og-image.png from HTML:
1. Open og-image-source.html in browser
2. Use browser screenshot tool (1200x630)
3. Save as og-image.png

Or use a tool like:
- https://htmlcsstoimage.com/
- Puppeteer script
- Chrome DevTools

## SSL Certificate

All hosting options above provide free SSL certificates automatically.

## DNS Settings

Point your domain to:
- Netlify: Follow their custom domain guide
- Vercel: Add CNAME record pointing to `cname.vercel-dns.com`
- GitHub Pages: A records to GitHub's IPs

## Contact

Cryptosam LLC
support@taskpomo.com