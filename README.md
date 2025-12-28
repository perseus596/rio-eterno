# Río Eterno - Spanish Website

This folder contains the Spanish version of the Río Eterno website.

## Files

- `index.html` - Main landing page in Spanish
- `politica-de-privacidad.html` - Privacy policy in Spanish

## Deploying to GitHub Pages

### Option 1: Create a new repository

1. Create a new GitHub repository (e.g., `rio-eterno-spanish`)
2. Initialize git in this folder:
   ```bash
   cd "/Users/Ferenc/Desktop/VIBECODING WITH CLAUDE/ENDLESS RIVER SPANISH/website"
   git init
   git add .
   git commit -m "Initial Spanish website"
   ```
3. Link to your GitHub repository:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/rio-eterno-spanish.git
   git branch -M main
   git push -u origin main
   ```
4. Go to your repository settings on GitHub
5. Navigate to "Pages" in the left sidebar
6. Under "Source", select "main" branch and "/" (root) folder
7. Click "Save"
8. Your site will be available at: `https://YOUR_USERNAME.github.io/rio-eterno-spanish/`

### Option 2: Use a subfolder in your existing repository

1. Copy these files to your existing `endless-river` repository:
   ```bash
   cd path/to/endless-river
   mkdir -p es
   cp "/Users/Ferenc/Desktop/VIBECODING WITH CLAUDE/ENDLESS RIVER SPANISH/website/index.html" es/
   cp "/Users/Ferenc/Desktop/VIBECODING WITH CLAUDE/ENDLESS RIVER SPANISH/website/politica-de-privacidad.html" es/
   git add es/
   git commit -m "Add Spanish website"
   git push
   ```
2. Your Spanish site will be available at: `https://perseus596.github.io/endless-river/es/`

## Privacy Policy URL

Once deployed, use this URL in App Store Connect:
- If Option 1: `https://YOUR_USERNAME.github.io/rio-eterno-spanish/politica-de-privacidad.html`
- If Option 2: `https://perseus596.github.io/endless-river/es/politica-de-privacidad.html`

## Contact Email

Support email for App Store listing: **endlessriverapp@gmail.com**
