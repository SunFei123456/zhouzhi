# ZZ Archive: The Zhou Zhi Estate

A memorial website for visual-systems researcher Zhou Zhi (1978–2022).

## Website Structure

```
zhouzhi/
├── index.html          # Language selection landing page
├── cn/                 # Chinese version
│   ├── index.html
│   └── images/
├── en/                 # English version
│   ├── index.html
│   └── images/
└── README.md
```

## Deployment Options

### Option 1: GitHub Pages (Recommended - Free)

1. **Create GitHub Repository**
   - Go to [github.com](https://github.com) and create a new repository
   - Name it `zhouzhi-archive` (or any name you prefer)
   - Make it public

2. **Upload Files**
   ```bash
   # If using git
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/YOUR_USERNAME/zhouzhi-archive.git
   git push -u origin main
   ```
   
   Or simply drag and drop files to GitHub web interface.

3. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: main / root
   - Save

4. **Access Your Site**
   - URL: `https://YOUR_USERNAME.github.io/zhouzhi-archive`
   - It may take a few minutes to deploy

### Option 2: Vercel (Recommended - Free)

1. Go to [vercel.com](https://vercel.com) and sign up
2. Click "Add New Project"
3. Import your GitHub repository
4. Deploy (default settings work fine)
5. Get a free `.vercel.app` domain

### Option 3: Netlify (Free)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your `zhouzhi` folder
3. Get a free `.netlify.app` domain

### Option 4: Cloudflare Pages (Free)

1. Go to [dash.cloudflare.com](https://dash.cloudflare.com)
2. Pages → Create a project
3. Connect to Git or upload directly
4. Deploy

### Option 5: Traditional Web Hosting

Upload all files via FTP to your web server's `public_html` directory.

## Custom Domain (Optional)

All platforms above support custom domains:
1. Purchase a domain (e.g., from GoDaddy, Namecheap, Alibaba Cloud)
2. Add domain in your hosting platform settings
3. Configure DNS records as instructed
4. Wait for DNS propagation (usually 24-48 hours)

## Local Preview

Simply double-click `index.html` to open in browser, or use a local server:

```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve .

# PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

## Features

- Bilingual support (Chinese / English)
- Responsive design
- Dark theme with CAD-inspired aesthetics
- Image preview functionality
- Loading animation with quotes
- System clock display

## Credits

- Design & Development: Zhou Zhi Estate Trust
- Content: Based on Zhou Zhi's life and work

## License

© Zhou Zhi Estate Trust. All rights reserved.
