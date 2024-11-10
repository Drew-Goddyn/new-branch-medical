# New Branch Medical Website

A static marketing website for New Branch Medical, an obesity and weight management clinic. The site is designed to be simple, elegant, and responsive, ensuring proper scaling across various devices.

## Features

- Fully responsive design
- Clean, modern interface
- Evidence-based approach presentation
- Easy contact form
- Mobile-friendly navigation

## Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript
- No build process required
- GitHub Pages compatible

## Local Development

1. Clone the repository:

## Deployment Instructions

### GitHub Pages Setup

1. Create a new repository on GitHub:
   - Go to github.com
   - Click "New Repository"
   - Name it: `new-branch-medical`
   - Keep it public
   - Don't initialize with README (we already have one)

2. Push to GitHub:
   ```bash
   git remote add origin https://github.com/[username]/new-branch-medical.git
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - Go to repository Settings
   - Navigate to "Pages" in the sidebar
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click Save

4. Your site will be published at:
   `https://[username].github.io/new-branch-medical`

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/[username]/new-branch-medical.git
   cd new-branch-medical
   ```

2. View locally:
   - Using Python:
     ```bash
     python -m http.server 8000
     ```
   - Or using VS Code:
     - Install "Live Server" extension
     - Right-click index.html
     - Select "Open with Live Server"

3. Make changes:
   ```bash
   git add .
   git commit -m "Description of changes"
   git push
   ```

### File Structure