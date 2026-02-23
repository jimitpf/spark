# SPARK Art Residency — Website
A single-page website for **SPARK Art Residency**, a nonprofit art residency program housed in a historic 1903 stone church at 820 Eastern Avenue, Schenectady, NY.
## About
SPARK Art Residency is founded by visual artist **Gunjan Tyagi** (MFA, Sir J.J. School of Arts, Mumbai). The program offers artists monumental studio space within a 15,000+ sq ft landmark church, with connections to galleries, collectors, and exhibits across the East Coast.
**Board of Directors:** Rodney Dickson, Anindita Dutta
## Tech Stack
- Pure HTML/CSS/JS — no frameworks, no build step
- Self-contained single page with smooth scroll navigation
- Responsive design (mobile, tablet, desktop)
- CSS animations and scroll-reveal effects
- Google Fonts: Cormorant Garamond + DM Sans
## Project Structure
```
spark-residency/
├── index.html          # Main website
├── images/             # Optimized image assets
│   ├── painting-*.jpg  # Gunjan Tyagi paintings
│   ├── installation-*.jpg  # Installation artwork
│   ├── gunjan-tyagi-founder.jpg
│   ├── anindita-dutta-board.jpg
│   ├── exhibition-community.jpg
│   └── divider-art-in-progress.jpg
└── README.md
```
## Deployment
This is a static site — deploy anywhere:
- **GitHub Pages:** Push to `main`, enable Pages in repo settings
- **Netlify:** Drag and drop the folder, or connect to this repo
- **Vercel:** Import the repo, it auto-detects static sites
### Quick deploy with Netlify:
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the entire `spark-residency` folder
3. Done — you'll get a live URL instantly
## Customization
- **Colors:** Edit CSS variables in `:root` at the top of `index.html`
- **Content:** All text is directly in the HTML
- **Images:** Replace files in `/images` folder, keep same filenames
- **Contact form:** Currently front-end only. Connect to [Formspree](https://formspree.io), [Netlify Forms](https://docs.netlify.com/forms/setup/), or a backend
- **Application:** "Express Interest" button uses `mailto:`. Replace with Google Form or Typeform link
## License
© 2025 SPARK Art Residency. All rights reserved.
Artwork images are © Gunjan Tyagi and Anindita Dutta respectively.
