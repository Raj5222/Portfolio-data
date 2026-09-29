# Portfolio Data Repository

A centralized, headless, and strongly-typed data repository serving dynamic content for Raj Sathvara's portfolio website.

## 📁 Repository Structure

```
├── bio.json          # Bio, roles, typewriter texts, contact links, metrics & summary
├── experiences.json  # Professional work experiences, promotions, metrics & achievements
├── Project.json      # Featured projects, screenshots, live URLs, repository links & tech stacks
├── skills.json       # Categorized technical competencies with SVG/PNG asset URLs
└── Education.json    # Formal academic degrees, institutions, CGPA, and coursework
```

## 🌐 Dynamic Endpoints (Raw GitHub API)

- **Bio**: `https://raw.githubusercontent.com/Raj5222/Portfolio-data/main/bio.json`
- **Experiences**: `https://raw.githubusercontent.com/Raj5222/Portfolio-data/main/experiences.json`
- **Projects**: `https://raw.githubusercontent.com/Raj5222/Portfolio-data/main/Project.json`
- **Skills**: `https://raw.githubusercontent.com/Raj5222/Portfolio-data/main/skills.json`
- **Education**: `https://raw.githubusercontent.com/Raj5222/Portfolio-data/main/Education.json`

## 🚀 How to Update Content

1. Edit any JSON file locally or directly on GitHub.
2. Commit and push changes:
   ```bash
   git add .
   git commit -m "Update portfolio data"
   git push origin main
   ```
3. The portfolio frontend automatically fetches the latest data via cache-busting queries with offline fallback via IndexedDB and Cache Storage.
