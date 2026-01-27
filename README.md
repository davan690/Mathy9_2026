# Mathy9_2026
Resources, tools and links for my year 9 maths class.

## Year 9 Mathematics Website

This repository contains a Quarto-based website for Year 9 Mathematics, aligned with the New Zealand Curriculum.

### Website Content

The website includes:
- **Home Page**: Welcome and course overview
- **7 Topic Pages**:
  1. Number and Operations
  2. Algebra
  3. Geometry
  4. Measurement
  5. Statistics
  6. Probability
  7. Ratios and Proportions
- **References**: Curriculum resources and learning materials

### Building the Website

To build the website, you need to have [Quarto](https://quarto.org/) installed.

```bash
# Preview the website locally
quarto preview

# Build the website
quarto render
```

The rendered website will be in the `docs/` directory.

### Deployment

The website can be deployed to:
- GitHub Pages (using the `docs/` folder)
- Netlify
- Any static hosting service

### Structure

- `_quarto.yml` - Quarto configuration file
- `*.qmd` - Quarto markdown files for each page
- `styles.css` - Custom CSS styling
- `docs/` - Generated website output (after rendering)
