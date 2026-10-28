# DataLab — Python for Data Analysis

A responsive, beginner-friendly learning website for Pandas, NumPy, Matplotlib, and Seaborn. Open `index.html` in a modern browser to start.

## Structure

- `index.html` — home and learning path
- `about.html` — approach and suggested order
- `pandas.html`, `numpy.html`, `matplotlib.html`, `seaborn.html` — separate library guides
- `practice.html` — exercises across the four libraries
- `mini-projects.html` — retail, student, and hospital projects
- `interview-questions.html` — library-specific interview preparation
- `cheat-sheet.html` — compact syntax reminders
- `contact.html` — accessible demo contact form
- `assets/css/styles.css` — shared theme and responsive layout
- `assets/js/main.js` — navigation, lesson content, and small interactions

The project uses plain HTML, CSS, and JavaScript. The lesson pages are static files; their detailed lesson cards are rendered from the shared `main.js` library content. The contact form is a front-end demo and needs a form service to deliver messages.

## Deployment with GitHub Pages

After enabling GitHub Pages for this repository, the site will be available at:

**Expected site URL:** https://charanmareddy.github.io/python-data-analysis-learning/

To deploy this plain HTML/CSS/JavaScript site:

1. Open the repository’s **Settings → Pages** on GitHub.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then save.
4. Wait for GitHub Pages to publish the site, then open the URL above.

The URL is expected; it is not live until Pages finishes its first deployment.
