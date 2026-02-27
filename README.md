# R for Novices - Gapminder Lessons

An adapted version of [Software Carpentry's R-novice-gapminder](https://swcarpentry.github.io/r-novice-gapminder/) course, designed to provide a clearer, more focused learning experience for both instructors and students.

🌐 **[View the lessons online](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/)**

## About This Course

This website presents R programming lessons in a decluttered, streamlined format that makes learning easier and more enjoyable. Whether you're an instructor teaching a workshop or a student learning independently, these lessons provide:

- Clear, focused content without unnecessary complexity
- Step-by-step examples using real-world data (Gapminder dataset)
- Hands-on exercises to practice your skills
- A clean, modern interface for easy navigation

## Lessons

1. **[Exploring Data Frames](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/exploring_dataframes.html)** - Learn to manipulate and explore data frames in R
2. **[Subsetting Data](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/data_subsetting.html)** - Master techniques for extracting subsets of data
3. **[Control Flow](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/control_flow.html)** - Make decisions with if/else statements and repeat operations with loops
4. **[Creating Publication-Quality Graphics with ggplot2](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/ggplot2.html)** - Build professional visualizations using the grammar of graphics
5. **[Functions Explained](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/functions.html)** - Understand and create your own R functions
6. **[Writing Data](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/writing_data.html)** - Learn to export and save your data
7. **[Data Frame Manipulation with dplyr](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/dplyr.html)** - Master data wrangling with dplyr verbs and pipes

## Who Is This For?

- **Instructors**: Use these materials for teaching R programming workshops
- **Students**: Follow along during class or work through lessons independently
- **Self-learners**: Build your R programming skills at your own pace

## Getting Started

No installation required! Simply visit the [website](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/) and start learning.

To follow along with the lessons, you'll need:
- R (version 4.0 or higher)
- RStudio (recommended)
- The gapminder package: `install.packages("gapminder")`

## Credits

- **Original Content**: [Software Carpentry's R for Reproducible Scientific Analysis](https://swcarpentry.github.io/r-novice-gapminder/)
- **Adaptation**: Samuel Bharti
- **AI Assistance**: Generated and adapted with GitHub Copilot

## License

This work is licensed under [CC BY 4.0](LICENSE.md), following Software Carpentry's licensing. You are free to share and adapt these materials with attribution.

---

## For Developers

### Project Structure

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

To build lessons and slides together:
```powershell
./build.ps1
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
