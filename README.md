<div align="center">

# 📊 Dataframes

<p><strong>A beginner-friendly R + Quarto teaching module for understanding data frames</strong></p>

<p>
  <a href="https://madelineratoza.github.io/Dataframes/"><img alt="Live Site" src="https://img.shields.io/badge/Live%20Module-GitHub%20Pages-blue"></a>
  <img alt="Built with Quarto" src="https://img.shields.io/badge/Built%20with-Quarto-39729E">
  <img alt="Language" src="https://img.shields.io/badge/Language-R-276DC3">
  <img alt="Status" src="https://img.shields.io/badge/Status-Educational-success">
</p>

</div>

---

## Overview

**Dataframes** is a short instructional website designed to help beginners understand what a data frame is, why structure matters, and how organized data supports reproducible analysis in R.

The module introduces core ideas such as:

- rows as observations
- columns as variables
- clean data structure principles
- asking answerable questions with code
- using simple `dplyr` workflows to explore tabular data

This repo is especially useful for learners moving from spreadsheet-based work toward reproducible data workflows.

---

## 🌐 Live Module

👉 **View the site here:**  
**[madelineratoza.github.io/Dataframes](https://madelineratoza.github.io/Dataframes/)**

---

## What You'll Learn

The module walks learners through:

- **What a data frame is**
- **Why data structure matters**
- **How rows and columns work together**
- **How to define the unit of observation**
- **How to organize data before analysis**
- **How to answer simple questions in R**

Example concepts include:

```r
nrow(df)
names(df)

df %>%
  summarize(avg_grade = mean(final_grade))

df %>%
  group_by(course) %>%
  summarize(n = n(), avg_grade = mean(final_grade))
```

---

## Module Snapshot

The main lesson explains a data frame as a table where:

- **each row is one observation**
- **each column is one variable**

It also includes a small example dataset and a practical checklist for deciding whether a dataset is ready for analysis.

---

## Repository Structure

```text
Dataframes/
├── docs/                              # Rendered website output for GitHub Pages
├── index.qmd                          # Main landing page / module introduction
├── What is Data Science.qmd           # Supporting lesson content
├── What is Data Science?.qmd          # Alternate or earlier version
├── Basics Excel and R.qmd             # Introductory teaching material
├── From Excel to Reproducible Workflows.qmd
├── Resources.qmd                      # Additional resources
├── _quarto.yml                        # Quarto site configuration
└── README.md                          # Project overview
```

---

## Built With

- **R**
- **Quarto**
- **GitHub Pages**
- **dplyr**

---

## Local Development

To run or edit this project locally:

### 1. Clone the repository

```bash
git clone https://github.com/madelineratoza/Dataframes.git
cd Dataframes
```

### 2. Open the project

Open the files in **RStudio** or your preferred editor.

### 3. Render the site

```bash
quarto render
```

### 4. Preview locally

```bash
quarto preview
```

---

## Publishing

This site is configured as a **Quarto website** with output directed to the `docs/` folder, which makes it compatible with **GitHub Pages** publishing.

If you update the content:

1. Edit the `.qmd` files
2. Render the site with `quarto render`
3. Commit and push the updated files in `docs/`

---

## Intended Audience

This project is for:

- students new to R
- beginners learning data organization
- instructors teaching foundational data concepts
- learners transitioning from Excel to reproducible workflows

---

## Why This Project Matters

Understanding data frames is one of the most important early steps in learning data analysis. Before learners write complex code, they need a clear mental model of:

- what one row represents
- what one column represents
- how consistent structure makes analysis possible

This repository helps build that foundation in a simple, approachable way.

---

## Contributing

Suggestions for improving clarity, examples, visuals, or beginner accessibility are welcome. Contributions can include:

- content edits
- cleaner examples
- additional beginner exercises
- improved page design and navigation

---

## License

Add a license section here if you plan to make reuse permissions explicit.

For example:

```text
MIT License
```

---

<div align="center">
  <sub>Made for teaching, learning, and building confidence with structured data.</sub>
</div>
