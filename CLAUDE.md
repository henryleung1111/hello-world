# CLAUDE.md - AI Assistant Guide

## Project Overview

This is a learning-focused "hello-world" repository for exploring Git, GitHub, and R programming. The repository owner is studying data science through the Johns Hopkins University track on Coursera.

## Repository Structure

```
hello-world/
├── README.md      # Project description and learning context
└── CLAUDE.md      # This file - AI assistant guidelines
```

## Current State

- **Primary Focus**: Learning R programming and data science fundamentals
- **Git Workflow**: Basic branching with pull request merges
- **Complexity Level**: Beginner/starter repository

## Development Guidelines

### For AI Assistants

1. **Keep explanations beginner-friendly**: The user is learning R and data science fundamentals. Provide clear, educational explanations.

2. **Prioritize learning over complexity**: When suggesting solutions, prefer simple, readable code over advanced patterns.

3. **Include comments**: When writing R code, include helpful comments explaining what each section does.

4. **Suggest best practices gradually**: Introduce good habits (version control, documentation, reproducible research) in a supportive way.

### Code Style Conventions

When adding R code to this repository:

- Use descriptive variable names
- Include comments for non-obvious operations
- Follow tidyverse style guide when applicable
- Keep scripts modular and well-organized

### Git Workflow

- **Main branch**: Stable, working code
- **Feature branches**: For new experiments or features
- **Commit messages**: Use clear, descriptive messages explaining what changed and why

## Common Tasks

### Adding New R Scripts

When creating new R scripts, consider this structure:

```r
# Script: [name].R
# Purpose: [brief description]
# Author: [name]
# Date: [date]

# Load required libraries
# library(...)

# Main code here
```

### Data Science Projects

For Coursera assignments or data science projects:

1. Create a dedicated folder for each project/assignment
2. Include a README explaining the project goals
3. Keep data files separate from code
4. Document data sources and any preprocessing steps

## Resources

- [R for Data Science](https://r4ds.had.co.nz/) - Recommended companion book
- [Coursera Data Science Specialization](https://www.coursera.org/specializations/jhu-data-science) - Primary learning track
- [GitHub Guides](https://guides.github.com/) - For Git/GitHub fundamentals

## Notes for Future Development

As this repository grows, consider:

- Adding a `.gitignore` file for R projects (ignoring `.Rhistory`, `.RData`, etc.)
- Organizing projects into subdirectories
- Using R Markdown (`.Rmd`) for reproducible reports
- Setting up an R project file (`.Rproj`) for RStudio integration
