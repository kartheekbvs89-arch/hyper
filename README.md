# HyperTune

**The complete hyperparameter tuning reference for ML & DL engineers.**

A deeply educational, article-style course modeled after [mlcourse.ai](https://mlcourse.ai), covering hyperparameter tuning from first principles to production. Built as a static multi-page website with a dark-themed UI, MathJax-rendered math, runnable Python code blocks, inline SVG diagrams, callout boxes, and per-module assignments with solutions.

## Course curriculum (12 modules)

| # | Module | Tag | Articles |
|---|--------|-----|----------|
| 01 | Foundations of Hyperparameter Tuning | Basics | 3 + assignment |
| 02 | Grid Search — Exhaustive Tuning | ML | 2 + assignment |
| 03 | Random Search — Smart Sampling | ML | 1 + assignment |
| 04 | Hyperparameters by Model Type — ML Deep Dive | ML | 4 + assignment |
| 05 | Deep Learning Hyperparameters — Neural Networks | DL | 2 + assignment |
| 06 | Bayesian Optimization — Intelligent Search | DL | 2 + assignment |
| 07 | Advanced Search Strategies | Advanced | 1 + assignment |
| 08 | Learning Rate Scheduling Mastery | DL | 1 + assignment |
| 09 | AutoML & Neural Architecture Search | Advanced | 1 + assignment |
| 10 | Pipeline Integration & Best Practices | Production | 1 + assignment |
| 11 | Analysis & Visualization of Tuning Results | Advanced | 1 + assignment |
| 12 | Production-Grade Tuning at Scale | Production | 1 + assignment |

## Site structure

```
/
├── index.html                  ← landing page with curriculum
├── module01/
│   ├── intro.html              ← module overview
│   ├── part1_params_vs_hyperparams.html
│   ├── part2_bias_variance.html
│   ├── part3_cross_validation.html
│   ├── assignment_task.html
│   └── assignment_solution.html
├── module02/  ...  module12/   ← same pattern
```

## Features

- **Dark-themed, self-contained HTML** — every page inlines its own CSS, JS, and MathJax. No build step.
- **Left sidebar TOC with scrollspy** — like Jupyter Book.
- **Prev/Next navigation** between every article.
- **MathJax-rendered equations** with full symbol explanations.
- **Runnable Python code blocks** using scikit-learn, XGBoost, LightGBM, PyTorch, Optuna, scikit-optimize, MLflow, Ray Tune.
- **Callout boxes** (note / tip / warning / important) throughout.
- **Inline SVG diagrams** for bias-variance curves, GP posteriors, SHA brackets, LR schedules, Pareto fronts, etc.
- **Jupyter-style assignment cells** with `# YOUR CODE HERE` placeholders and grading rubrics.
- **Real datasets** — breast_cancer, digits, wine, iris, Adult Census, CIFAR-10.

## Tech stack

- Python 3.10+
- scikit-learn 1.4+
- XGBoost / LightGBM
- PyTorch 2.0+
- Optuna 3.0+
- scikit-optimize, MLflow, Ray Tune, W&B (referenced in later modules)

## Browsing

Just open `index.html` in any modern browser. The site is fully static — no server, no build step. Cross-module navigation uses relative paths so it works equally well on GitHub Pages, Netlify, or your local filesystem.

## License

Educational use. See individual article footers for source attributions.
