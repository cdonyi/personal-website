# Personal Website

A modern, responsive personal website built with HTML, CSS, and vanilla JavaScript. Showcases my work as a software engineer, explorer, and storyteller.

## Features

- **Responsive Design**: Optimized for all devices
- **Smooth Animations**: CSS animations and transitions
- **Clean Typography**: Custom font stack with Google Fonts
- **Accessibility**: Semantic HTML and proper contrast ratios
- **Fast Loading**: Minimal dependencies, optimized assets

## Tech Stack

- HTML5
- CSS3 (Custom properties, Grid, Flexbox)
- Vanilla JavaScript (minimal)
- Google Fonts (Lora, DM Sans, Playfair Display)
- Netlify for deployment

## Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/cdonyi/personal-website.git
   cd personal-website
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

## Deployment

This site is configured for Netlify deployment:

- Build command: (empty - static site)
- Publish directory: `.`
- The `netlify.toml` file handles the configuration

## Project Structure

```
personal-website/
├── index.html          # Main HTML file
├── netlify.toml        # Netlify deployment config
└── README.md          # This file
```

## TODO / What's Left to Do

Based on recent commits and current state:

### High Priority
- [ ] **Uncomment and populate Projects section**: The projects grid is currently commented out in `index.html`. Add real project showcases with:
  - Project thumbnails/images
  - Live demo links
  - Source code links
  - Technology tags

- [ ] **Create actual blog content**: Replace placeholder blog posts with real articles:
  - "Dipping my toes in Claude Code and AI tooling"
  - "USSF Coaching Accreditation Journey" 
  - "My Coding Playlist: Albums for Deep Work"

### Medium Priority
- [ ] **Add project images/assets**: Replace emoji placeholders with actual project screenshots
- [ ] **Implement blog functionality**: Either create separate HTML pages for posts or integrate a static site generator
- [ ] **Add contact form**: Replace email link with a functional contact form
- [ ] **SEO optimization**: Add meta tags, Open Graph, structured data

### Low Priority
- [ ] **Add analytics**: Integrate Google Analytics or similar
- [ ] **Performance optimization**: Minify CSS, optimize images
- [ ] **Dark mode toggle**: Add theme switching functionality
- [ ] **Add more sections**: Testimonials, resume download, etc.

### Content Updates
- [ ] **Update footer**: Ensure copyright year and location are current
- [ ] **Personal info**: Verify all contact links and personal details are up to date
- [ ] **Add more interests/hobbies**: Expand the about section with additional passions

## Contributing

This is a personal project, but feel free to open issues for bugs or suggestions.

## License

© 2026 Donald Onyango. All rights reserved.