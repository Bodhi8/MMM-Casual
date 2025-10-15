

This repo contains a sequence of eight concise, runnable **Jupyter notebooks** to learn practical **marketing analytics, econometrics, and causal inference** with toy datasets. Each notebook is self-contained—open, run all cells, and explore.

 (Run Order)

1. **`01_mmm_intro.ipynb`** — Intro to Media Mix Modeling (MMM) with adstock & saturation. *Key concepts:* regression, ROI estimation.
2. **`02_mmm_fundamentals_tuning.ipynb`** — MMM fundamentals and adstock tuning. *Key concepts:* model fit, parameter search.
3. **`03_mmm_tree_and_importance.ipynb`** — Tree‑based MMM with feature importance. *Key concepts:* random forests, attribution.
4. **`04_causal_basics_ate.ipynb`** — Causal inference and treatment effects. *Key concepts:* confounding, matching, ATE.
5. **`05_dml_crossfitting.ipynb`** — Double Machine Learning (DML) demonstration. *Key concepts:* cross‑fitting, causal ML.
6. **`06_mmm_kpi_viz.ipynb`** — Visualizing KPIs and correlations. *Key concepts:* exploratory data analysis.
7. **`07_mmm_pitfalls_diagnostics.ipynb`** — Model diagnostics and pitfalls. *Key concepts:* multicollinearity, residuals, VIF.
8. **`08_attribution_markov.ipynb`** — Markov‑chain attribution. *Key concepts:* journey modeling, channel contribution.

## Setup

```bash
pip install -r requirements.txt
jupyter notebook
```

**Minimal `requirements.txt`**

- numpy
- pandas
- matplotlib
- scikit-learn
- statsmodels

## Suggested Extensions

- Add budget optimization to the MMM notebooks.
- Try `DoWhy` or `EconML` for richer causal analysis.
- Wrap any notebook into a small **FastAPI** or **Streamlit** app.
- Visualize attribution paths with `networkx` or `plotly`.

## References

1. Marketing Mix Modeling with PyMC — PyMC Marketing Docs  
2. Causal Inference Tutorial — MIT Economics  
3. Double Machine Learning — Chernozhukov et al.  
4. Storytelling with Data — Cole Nussbaumer Knaflic
