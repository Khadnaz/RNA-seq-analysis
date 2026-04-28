# Exploratory RNA-seq analysis report

This repository contains an executed Jupyter notebook report.

## View the report

- Main notebook: [`minimal-rnaseq-ibex-report.executed.ipynb`](minimal-rnaseq-ibex-report.executed.ipynb)
- Static HTML export: [`minimal-rnaseq-ibex-report.html`](minimal-rnaseq-ibex-report.html)

For the closest visual match to the original notebook, publish the `docs/` folder with GitHub Pages. The exported HTML is copied to `docs/index.html`.

## Files

```text
.
├── README.md
├── minimal-rnaseq-ibex-report.executed.ipynb
├── minimal-rnaseq-ibex-report.html
├── requirements.txt
├── .gitignore
└── docs/
    ├── index.html
    └── .nojekyll
```

## Re-running the notebook

The notebook already contains saved outputs, so it can be viewed on GitHub without re-running. To re-run it, you will also need the original input files referenced inside the notebook.

Install the basic Python dependencies with:

```bash
pip install -r requirements.txt
```

## Notes

GitHub renders `.ipynb` notebooks as static HTML. Keep the notebook outputs saved if you want figures and tables to appear on GitHub.
