# Lucas de Souza Lima | Technical Portfolio

[![Live Portfolio](https://img.shields.io/badge/Live_Portfolio-Visit_Site-0D8A76?style=for-the-badge)](https://lslima123.github.io/)
[![GitHub](https://img.shields.io/badge/GitHub-lslima123-153B5B?style=for-the-badge&logo=github)](https://github.com/lslima123)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Lucas_Lima-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/lucas-lima-8832b0267/)

A unified technical portfolio connecting three areas of work:

- **Build** - software development, Python tooling, APIs, and automation.
- **Analyze** - data science, machine learning, time-series analysis, and quantitative modeling.
- **Secure** - cybersecurity, offensive security research, reconnaissance, and technical writeups.

The portfolio presents Mathematics as the analytical foundation behind these disciplines and highlights practical projects that combine rigorous reasoning with real-world software and systems.

## Live website

**[lslima123.github.io](https://lslima123.github.io/)**

## Portfolio highlights

### Flagship project

**Stock ML Lab** is an ongoing research framework for financial-return prediction built around reproducible experiments and honest out-of-sample evaluation.

Its methodology includes temporal cross-validation, classical and machine-learning baselines, hyperparameter optimization, bootstrap inference, transaction-cost analysis, and cross-asset robustness testing.

### Selected work

| Project | Areas | Description |
|---|---|---|
| [AWS Cloud Cost Analysis](https://github.com/lslima123/Desafio-ICT-Itau) | Data Science, ML | Data processing, exploratory analysis, and regression modeling for AWS instance-pricing data. |
| [WebRecon](https://github.com/lslima123/webrecon) | Python, Cybersecurity | Web reconnaissance toolkit for HTTP analysis, security-header inspection, and endpoint discovery. |
| [Gold Time-Series Analysis](https://github.com/lslima123/gold_discussion) | Data Science, Statistics | Statistical investigation of gold-price dynamics using stationarity tests and ARIMA models. |
| [NetRecon](https://github.com/lslima123/netrecon) | Python, Networking | Multi-threaded network reconnaissance with TCP scanning, host discovery, and banner grabbing. |
| [Diabetes Detection ML](https://github.com/lslima123/detec-o-diabetes-ml) | Machine Learning | Classification-model comparison focused on recall, class imbalance, and robust evaluation. |
| [Flask To-Do](https://github.com/lslima123/flask-todo) | Software Development | Compact Flask application demonstrating backend fundamentals and persistence. |

### Security case studies

- [Silentium - Hack The Box](https://github.com/lslima123/Silentium---Hack-The-Box-Writeup)
- [Pickle Rick - TryHackMe](https://github.com/lslima123/Pickle-Rick---TryHackMe-Writeup)
- [Bounty Hacker - TryHackMe](https://github.com/lslima123/Bounty-Hacker---TryHackMe-Writeup)

## Features

- Responsive one-page interface for desktop, tablet, and mobile.
- Unified **Build / Analyze / Secure** professional narrative.
- Filterable project gallery using vanilla JavaScript.
- Dedicated flagship-project presentation.
- Security writeups presented as technical case studies.
- Downloadable unified technical CV.
- Accessible navigation, keyboard focus states, and reduced-motion support.
- Semantic HTML and metadata for search engines and social sharing.
- No frameworks, build tools, or runtime dependencies.

## Technology

| Layer | Tools |
|---|---|
| Structure | Semantic HTML5 |
| Styling | CSS3, custom properties, Grid, Flexbox, responsive media queries |
| Interaction | Vanilla JavaScript, Intersection Observer API |
| Typography | Inter, Space Mono |
| Hosting | GitHub Pages |

## Project structure

```text
lslima123.github.io/
├── index.html          # Content and semantic structure
├── style.css           # Visual system and responsive layouts
├── script.js           # Navigation, filters, and reveal interactions
├── assets/
│   └── cv.pdf          # Unified technical CV
└── README.md
```

## Run locally

The website is fully static. You can open `index.html` directly or serve the directory locally:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

No package installation or build command is required.

## Deploy with GitHub Pages

This repository is designed for GitHub Pages user-site deployment.

1. Keep the repository name as `lslima123.github.io`.
2. Place the website files in the repository root.
3. Commit and push the changes to the default branch.
4. In **Settings > Pages**, select deployment from the default branch if it is not already enabled.
5. Visit [lslima123.github.io](https://lslima123.github.io/) after GitHub finishes the deployment.

Example:

```bash
git add index.html style.css script.js assets/cv.pdf README.md
git commit -m "Redesign unified technical portfolio"
git push origin main
```

## Updating the portfolio

### Add a project

Add a new `.project-card` element to the project grid in `index.html` and assign one or more categories through `data-category`:

```html
<article class="project-card reveal" data-category="software data">
  <!-- Project content -->
</article>
```

Supported filters are:

- `software`
- `data`
- `security`

### Replace the CV

Export the new CV as PDF and replace:

```text
assets/cv.pdf
```

Keeping the filename unchanged prevents the download link from breaking.

### Publish Stock ML Lab

When its public repository is ready, add the repository URL to the flagship project section in `index.html` and update the project description here.

## Design direction

The interface deliberately avoids an exclusively "hacker" aesthetic. Its visual system combines a dark engineering-oriented layout with restrained green and blue accents, allowing software development, quantitative research, and cybersecurity work to share the same identity.

## Contact

- **Email:** [lslima123@proton.me](mailto:lslima123@proton.me)
- **GitHub:** [github.com/lslima123](https://github.com/lslima123)
- **LinkedIn:** [linkedin.com/in/lucas-lima-8832b0267](https://www.linkedin.com/in/lucas-lima-8832b0267/)
- **Portfolio:** [lslima123.github.io](https://lslima123.github.io/)

---

Built with HTML, CSS, and JavaScript by **Lucas de Souza Lima**.
