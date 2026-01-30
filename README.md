# R for Novices - Gapminder Lessons

An adapted version of [Software Carpentry's R-novice-gapminder](https://swcarpentry.github.io/r-novice-gapminder/) course, designed to provide a clearer, more focused learning experience for both instructors and students.

## About This Project

This website declutters and streamlines the original Software Carpentry content, making it ideal for:
- **Instructors** teaching R programming side-by-side with students
- **Students** following along independently at their own pace
- **Self-learners** wanting clear, focused R programming lessons

The lessons maintain the core learning objectives while presenting content in a more accessible format.

## Lessons Included

1. **Exploring Data Frames** - Manipulate and explore data frames in R
2. **Subsetting Data** - Extract subsets of data effectively
3. **Functions Explained** - Create and understand R functions
4. **Writing Data** - Export and save your data

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
