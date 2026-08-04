# Contributing Guide

Thank you for contributing to the **Roy Plant–Microbiome Laboratory** website.

This document describes the workflow for updating and maintaining the website.

---

# Website Technology

This website is built using:

- Quarto
- HTML
- CSS
- Git
- GitHub Pages

Source files are written in `.qmd` format and rendered into the `docs/` directory.

---

# Project Structure

```
ThePlant-Roylawar.github.io

│
├── index.qmd
├── about.qmd
├── research.qmd
├── projects.qmd
├── team.qmd
├── publications.qmd
├── news.qmd
├── join.qmd
├── contact.qmd
│
├── styles.css
├── footer.html
├── images/
├── docs/
│
├── CHANGELOG.md
├── PROJECT_STATUS.md
├── WEBSITE_ROADMAP.md
├── DEVELOPMENT_LOG.md
└── CONTRIBUTING.md
```

---

# Development Workflow

Every change should follow the same workflow.

### 1. Edit files

Modify only the required files.

Example:

- index.qmd
- research.qmd
- styles.css

---

### 2. Render the website

```bash
quarto render
```

---

### 3. Review

Open the local website and verify:

- Desktop layout
- Mobile layout
- Images
- Links
- Typography

---

### 4. Git Status

```bash
git status
```

Review the modified files before committing.

---

### 5. Stage Changes

```bash
git add .
```

---

### 6. Commit

Use meaningful commit messages.

Examples:

```bash
git commit -m "Homepage v2.2: Add Latest News section"
```

```bash
git commit -m "Research page: Improve project cards"
```

---

### 7. Push

```bash
git push
```

---

# Website Design Principles

The website should:

- Maintain a clean academic appearance.
- Use original laboratory images whenever possible.
- Prioritize readability.
- Follow responsive design.
- Keep a consistent green colour palette.
- Avoid unnecessary visual clutter.
- Maintain consistent spacing across all pages.

---

# Editing Rules

Before making changes:

- Work on one feature at a time.
- Render after every major change.
- Review visually before committing.
- Avoid editing multiple unrelated sections in one commit.

---

# Homepage Structure

The homepage follows this fixed structure.

1. Hero
2. About the Lab
3. Research Impact
4. Featured Research
5. Research Collaborations
6. Latest News
7. Join the Lab
8. Footer

This structure should remain consistent unless there is a compelling reason for a future redesign.

---

# Documentation

Whenever a milestone is completed, update:

- CHANGELOG.md
- PROJECT_STATUS.md

If the project direction changes significantly, update:

- WEBSITE_ROADMAP.md
- DEVELOPMENT_LOG.md

---

# Branch Strategy

Development currently occurs on the `master` branch.

Future improvements may use feature branches before merging into the main website.

---

# Contact

Project Owner

**Dr. Praveen B. Roylawar**

Department of Botany

S. N. Arts, D.J.M. Commerce & B.N.S. Science College (Autonomous)

Sangamner, Maharashtra, India