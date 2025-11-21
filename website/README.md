# Beeline: Measuring and Minimizing Interaction Friction

A modern, responsive website promoting the Beeline research project - an open-source framework to measure and minimize "conversational friction" in Large Language Models.

## Project Overview

Beeline develops an open-source framework to measure and minimize "conversational friction" in Large Language Models (LLMs). The project addresses the fundamental problem of wasted time and computation in prompt refinement through a comprehensive three-part solution:

1. **Metric (I2R)**: Interaction-to-Resolution metric quantifying effort required to reach user satisfaction
2. **Benchmark**: Automated test suite on sovereign European infrastructure
3. **Middleware**: Proactive clarification library for developers

## Website Features

- Modern, responsive design
- Smooth scrolling navigation
- Fade-in animations on scroll
- Mobile-friendly layout
- Clean, professional aesthetic

## GitHub Pages Setup

To deploy this website on GitHub Pages:

1. **Create a GitHub repository** (if you haven't already):
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Beeline project website"
   git branch -M main
   git remote add origin https://github.com/[your-username]/beeline.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click on **Settings**
   - Scroll down to **Pages** section
   - Under **Source**, select **main** branch and **/ (root)** folder
   - Click **Save**

3. **Your site will be available at**:
   `https://[your-username].github.io/beeline/`

## Local Development

To view the website locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/[your-username]/beeline.git
   cd beeline
   ```

2. Open `index.html` in your web browser, or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

3. Navigate to `http://localhost:8000` in your browser

## Customization

### Update GitHub Link
Edit the GitHub link in `index.html` (line ~XXX):
```html
<a href="https://github.com/[your-username]/beeline" ...>
```

### Update Contact Information
Edit the contact section in `index.html` to add your email and phone number.

### Modify Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #7c3aed;
    /* ... */
}
```

## Project Information

- **Lead Organization**: aivb.ai
- **Partner**: natalia
- **Country**: Italy
- **Fund**: NGI Zero Commons Fund
- **Duration**: 12 Months
- **License**: Apache 2.0/MIT

## License

This website is open source and available under Apache 2.0/MIT License.

---

Part of the NGI Zero Commons Fund initiative

