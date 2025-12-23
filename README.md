# ToxicApps - Security Awareness Platform

A modern, scientific-style landing page promoting security awareness for application users in today's digital world.

## 🌐 Live Site

- **URL:** https://toxicapps.com
- **GitHub Repository:** https://github.com/mrcode718/toxicapps.home

## 🎨 Features

- Modern, scientific design with toxic/warning theme
- Responsive layout for all devices
- Animated statistics and interactive elements
- Smooth scrolling navigation
- Security-focused content and messaging
- SEO optimized

## 📁 Project Structure

```
toxicapps/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet with modern design
├── script.js           # Interactive JavaScript
├── CNAME               # GitHub Pages custom domain config
├── .nojekyll           # Disable Jekyll processing
├── .gitignore          # Git ignore file
├── README.md           # This file
└── DNS_CONFIGURATION.md # DNS setup guide
```

## 🚀 Deployment to GitHub Pages

### Prerequisites

- Git installed on your system
- GitHub account with access to `mrcode718/toxicapps.home` repository
- SSH key configured (or use HTTPS with Personal Access Token)

### Initial Setup

1. **Clone the repository** (if not already cloned):
   ```bash
   git clone git@github.com:mrcode718/toxicapps.home.git
   cd toxicapps.home
   ```

2. **Copy files to repository**:
   ```bash
   # If files are in a different location
   cp -r /path/to/toxicapps/* .
   ```

3. **Add and commit files**:
   ```bash
   git add .
   git commit -m "Initial commit: Add ToxicApps landing page"
   ```

4. **Push to GitHub**:
   ```bash
   git push origin main
   ```
   
   **Note:** If your default branch is `master`, use:
   ```bash
   git push origin master
   ```

### Enable GitHub Pages

1. Go to your repository on GitHub: `https://github.com/mrcode718/toxicapps.home`
2. Navigate to **Settings** → **Pages**
3. Under **Source**, select:
   - **Branch:** `main` (or `master` if that's your default branch)
   - **Folder:** `/ (root)`
4. Click **Save**

### Configure Custom Domain

1. In **Settings** → **Pages**, scroll to **Custom domain**
2. Enter: `toxicapps.com`
3. Click **Save**
4. GitHub will create/update the `CNAME` file automatically

### DNS Configuration

Follow the detailed instructions in [DNS_CONFIGURATION.md](./DNS_CONFIGURATION.md) to configure your domain's DNS records.

**Quick Summary:**
- Add 4 A records pointing to GitHub Pages IPs (185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153)
- Add CNAME record for www subdomain pointing to `mrcode718.github.io`
- Wait for DNS propagation (up to 48 hours)
- Enable HTTPS enforcement in GitHub Pages settings

## 🔧 Local Development

1. **Clone the repository**:
   ```bash
   git clone git@github.com:mrcode718/toxicapps.home.git
   cd toxicapps.home
   ```

2. **Open in browser**:
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Python 3
     python3 -m http.server 8000
     
     # Node.js (with http-server)
     npx http-server
     
     # PHP
     php -S localhost:8000
     ```

3. **Access locally**:
   - Open `http://localhost:8000` in your browser

## 📝 Making Updates

1. **Make changes** to HTML, CSS, or JavaScript files
2. **Test locally** before pushing
3. **Commit changes**:
   ```bash
   git add .
   git commit -m "Description of changes"
   git push origin main
   ```
4. **Changes will be live** on GitHub Pages within a few minutes

## 🎨 Customization

### Colors

Edit CSS variables in `styles.css`:
```css
:root {
    --primary-toxic: #ff4444;
    --secondary-toxic: #ff6b35;
    --warning-yellow: #ffd700;
    /* ... more colors ... */
}
```

### Content

- Edit `index.html` to change text content
- Modify sections, add new sections, or remove existing ones
- Update statistics in the hero section

### Styling

- All styles are in `styles.css`
- Responsive breakpoints are defined in media queries
- Animations can be adjusted in CSS keyframes

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔒 Security Features

- HTTPS enforced (after DNS configuration)
- No external dependencies (except Google Fonts)
- No tracking scripts
- Privacy-focused design

## 📄 License

This project is open source. Feel free to use and modify as needed.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📧 Support

For issues or questions:
- Open an issue on GitHub
- Check [DNS_CONFIGURATION.md](./DNS_CONFIGURATION.md) for DNS-related questions

## 🎯 Future Enhancements

Potential features to add:
- Blog section for security articles
- App security scanner tool
- User submission form for reporting toxic apps
- API integration for real-time threat data
- Multi-language support

---

**Built with ❤️ for security awareness**

