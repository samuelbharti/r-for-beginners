# R for Novices - Gapminder Lessons

## Project Structure

```
├── index.qmd              # Homepage (renders to docs/index.html)
├── lessons/               # Lesson source files (.qmd)
│   └── exploring_dataframes.qmd
├── docs/                  # Generated website (for GitHub Pages)
│   ├── index.html
│   └── lessons/
│       └── exploring_dataframes.html
└── _quarto.yml           # Website configuration
```

## Build the Website

Run in PowerShell or Terminal:
```bash
quarto render
```

Or in RStudio: Open `index.qmd` and click **Render**

## Deploy to GitHub Pages

1. **Build the site:** `quarto render`
2. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Update website"
   git push origin main
   ```
3. **Enable GitHub Pages:**
   - Go to repository Settings > Pages
   - Source: `main` branch
   - Folder: `/docs`
   - Save

Your site will be at: `https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/`

## Add More Lessons

1. Create new `.qmd` file in `lessons/` directory
2. Add to navbar in `_quarto.yml`
3. Run `quarto render`
