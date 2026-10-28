# DataLab — Python for Data Analysis

**Live website:** [https://charanmareddy.github.io/python-data-analysis-learning/](https://charanmareddy.github.io/python-data-analysis-learning/)

DataLab is a beginner-friendly, interactive learning website for people who want to use Python for data analysis. It introduces four widely used libraries—Pandas, NumPy, Matplotlib, and Seaborn—with plain-language explanations, practical examples, small exercises, and mini projects.

The site is built with HTML, CSS, and JavaScript. It is a learning resource, not a Python course environment: run the Python examples in your own notebook or Python installation.

## What you can learn here

- **Pandas:** load, inspect, select, clean, group, and combine table-shaped data.
- **NumPy:** create arrays and perform numerical calculations, comparisons, and transformations.
- **Matplotlib:** build and customize charts using figures and axes.
- **Seaborn:** explore distributions and relationships with statistical charts.
- **Practice:** revisit each library through short questions and coding exercises.
- **Mini Projects:** work through retail sales, student outcomes, and hospital waiting-time examples with runnable code and sample outputs.
- **Interview Questions:** prepare library-specific beginner, intermediate, and scenario-based answers.
- **Cheat Sheet:** review common syntax and analysis steps.

Each library has its own guide so its concepts and methods are taught in context. Examples use small, fictional datasets. The contact form is a front-end demonstration and does not send or store messages.

## A suggested way to learn

1. **Start with the Pandas guide.** Learn what rows, columns, data types, and missing values mean. Practise inspecting and filtering a small table.
2. **Study NumPy next.** Get comfortable with arrays, shape, data types, axes, and calculations. Check shapes whenever you combine or reshape arrays.
3. **Learn chart basics with Matplotlib.** Practise choosing a chart, labeling axes with units, adding a useful title, and checking scales before sharing it.
4. **Explore statistical charts with Seaborn.** Use tidy data to compare groups and distributions. Learn what each chart summarizes before drawing conclusions.
5. **Try the practice questions.** Attempt each prompt before looking back at the guide. Run code on a small dataset and explain the result in your own words.
6. **Complete a mini project.** Start with one clear question, inspect and clean the data, calculate a result, make a chart, and explain assumptions and limitations.
7. **Review the interview questions and cheat sheet.** Use them to check your understanding after you have practised, not as a substitute for practice.

### A helpful routine for each topic

- Read the concept and connect it to a table or question you understand.
- Type the example yourself rather than only copying it.
- Predict what the code will return, then run it and compare.
- Change one value or parameter and observe how the result changes.
- Check data types, shapes, missing values, and chart labels.
- Write a short explanation of what the result does—and does not—show.

## Getting started with the Python examples

Install Python, then open a terminal and install the four libraries:

```bash
python -m pip install pandas numpy matplotlib seaborn
```

You can run the examples in a Jupyter notebook or a Python script. For example, create a file named `first_analysis.py` and start it with:

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

The code samples on the site often include their own imports and sample data, so you can also run one project example at a time. A notebook is useful for beginners because it lets you run code in small cells and inspect each result.

## Pages

- `index.html` — Home and learning path
- `about.html` — project goals and suggested route
- `pandas.html` — Pandas guide
- `numpy.html` — NumPy guide
- `matplotlib.html` — Matplotlib guide
- `seaborn.html` — Seaborn guide
- `practice.html` — library practice prompts
- `mini-projects.html` — complete guided example projects
- `interview-questions.html` — interview preparation
- `cheat-sheet.html` — quick reference
- `contact.html` — demo contact form

## Project structure

```text
python-data-analysis-learning/
├── index.html
├── about.html
├── pandas.html
├── numpy.html
├── matplotlib.html
├── seaborn.html
├── practice.html
├── mini-projects.html
├── interview-questions.html
├── cheat-sheet.html
├── contact.html
└── assets/
    ├── css/styles.css
    └── js/main.js
```

The library guide pages keep an HTML introduction and load detailed lesson sections from `assets/js/main.js`. Shared layout, colors, and responsive behavior are in `assets/css/styles.css`.

## Run the site locally

No build step is required. You can open `index.html` in a modern browser. For a local web server, run this command from the project folder:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Deployment

This site is published with GitHub Pages from the `main` branch and the repository root. The live link is at the top of this README.
