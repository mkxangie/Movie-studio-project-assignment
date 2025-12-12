# Movie Industry Analysis for New Studio

**Author:** Angela Mukami  
**Project:** Data Science Phase 2 - Movie Box Office Analysis

---

## Business Problem

Our company is creating a new movie studio and needs to understand what types of films perform best at the box office to guide production decisions.

**Stakeholder:** Head of New Movie Studio

---

## Data Sources

- **Box Office Mojo:** Revenue data for 3,387 movies (2010-2018)
- **IMDB Database:** Movie characteristics, genres, and ratings for 9,426 movies (2010-2018)
- **Merged Dataset:** 1,778 movies with complete box office and metadata

---

## Key Findings

1. **Adventure and Action genres dominate** - Adventure films average $93M, Action films average $73M in domestic box office
2. **Longer films generate higher revenue** - Films 120-150 minutes average $66M vs. $27M for short films
3. **Optimal runtime varies by genre** - Adventure and Action peak at 120-150 minutes, Comedy and Horror at 90-120 minutes

---

## Business Recommendations

1. **Prioritize Adventure Films (120-150 minutes)** for maximum commercial return
2. **Invest in Action Films (120-150 minutes)** for stable, high returns
3. **Maintain 90-minute minimum runtime** and avoid Documentary/Drama-focused projects

---

## Repository Contents

- `movie_studio_project.ipynb` - Complete analysis with code and visualizations
- `bom.movie_gross.csv` - Box office revenue data
- `genre_performance.png` - Genre analysis visualization
- `runtime_performance.png` - Runtime analysis visualization  
- `genre_runtime_comparison.png` - Genre-runtime interaction visualization
- `presentation.pdf` - Non-technical presentation (to be added)

---

## Technologies Used

Python, Pandas, SQLite, Matplotlib, Jupyter Notebook

