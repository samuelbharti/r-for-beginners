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

1. **Intro to R** - Get oriented with R and RStudio ([Page](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/rstudio-intro.html), [Slides](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/slides/rstudio-intro.html))
2. **Projects** - Organize your work with projects ([Page](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/project-management.html), [Slides](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/slides/project-management.html))
3. **Seeking Help** - Learn to find and use help effectively ([Page](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/seeking-help.html), [Slides](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/slides/seeking-help.html))
4. **Data Structures** - Understand vectors, lists, and data frames ([Page](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/data-structures.html), [Slides](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/slides/data-structures.html))
5. **Exploring Data Frames** - Explore and inspect data frames in R ([Page](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/exploring_dataframes.html), [Slides](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/slides/exploring_dataframes.html))
6. **Subsetting Data** - Extract subsets of data with base R ([Page](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/data_subsetting.html), [Slides](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/slides/data_subsetting.html))
7. **Control Flow** - Use conditionals and loops ([Page](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/control_flow.html), [Slides](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/slides/control_flow.html))
8. **ggplot2** - Create clear and effective graphics ([Page](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/ggplot2.html), [Slides](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/slides/ggplot2.html))
9. **Vectorization** - Write faster, cleaner code ([Page](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/vectorization.html), [Slides](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/slides/vectorization.html))
10. **Functions** - Build and use your own functions ([Page](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/functions.html), [Slides](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/slides/functions.html))
11. **Writing Data** - Export and save your data ([Page](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/writing_data.html), [Slides](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/slides/writing_data.html))
12. **dplyr** - Wrangle data with verbs and pipes ([Page](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/dplyr.html), [Slides](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/slides/dplyr.html))
13. **R Markdown** - Create reports with code and text ([Page](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/knitr-markdown.html), [Slides](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/slides/knitr-markdown.html))
14. **Writing Good Software** - Write readable, maintainable code ([Page](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/lessons/writing-good-software.html), [Slides](https://samuelbharti.github.io/sw-r-novice-gapminder-lessons/slides/writing-good-software.html))

## About These Lessons

These materials are designed as a **supplementary resource** for R programming workshops and independent learning. Whether you're an instructor teaching a workshop or a student learning on your own, you'll find:

- **Web pages** - Perfect for reading and reference
- **Slides** - Great for following along during live instruction

Use whichever format works best for your learning style!

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

Quick notes for contributors:
- Source lessons live in lessons/ and slides/.
- Lesson pages render to docs/lessons and slide decks render to docs/slides.
- The slide assets in docs/slides/site_libs must be committed for GitHub Pages.

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
