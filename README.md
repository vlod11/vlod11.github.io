# Personal Website

Professional developer portfolio and landing page.

## Quick Start

### Deploy to GitHub Pages (Free)

1. **Create a new repo on GitHub:**
   - Name it: `vlod11.github.io` (or `username.github.io`)
   - Public repository

2. **Push this code:**
   ```bash
   cd personal-website
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/vlod11/vlod11.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to repo Settings → Pages
   - Source: Deploy from branch `main` / root
   - Save

4. **Your site will be live at:**
   `https://vlod11.github.io`

## Customization

### Update Contact Info

Edit `index.html`:
- Line 100: Replace `vlad@example.com` with your email
- Line 104: Update GitHub link if needed
- Line 108: Add your LinkedIn URL

### Add More Projects

In `index.html`, find the `#projects` section and add more project cards:

```html
<div class="project-card">
    <h3>Your Project Name</h3>
    <p>Description of the project and technologies used.</p>
    <div class="project-tags">
        <span class="tag">Tech 1</span>
        <span class="tag">Tech 2</span>
    </div>
    <a href="https://github.com/..." class="project-link">View on GitHub →</a>
</div>
```

### Update Services Pricing

Edit the service cards in the `#services` section to match your rates.

## Local Development

Just open `index.html` in your browser. No build tools needed.

## Tech Stack

- Pure HTML/CSS/JavaScript (no frameworks)
- Mobile responsive
- Optimized for performance
- SEO-friendly

## License

MIT
