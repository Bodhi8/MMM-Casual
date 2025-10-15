Marketing Data Science Quick-Track Labs
Overview

This repository contains a sequence of eight concise, runnable Jupyter notebooks designed to help you master advanced marketing analytics, causal inference, and media modeling concepts.
Each notebook uses a self-contained toy dataset so you can explore real analytical techniques in minutes—ideal for learning, experimentation, or portfolio demonstrations.

Learning Sequence (Run Order)
#	Notebook	Focus	Key Concepts
1️⃣	01_mmm_intro.ipynb	Intro to Media Mix Modeling (MMM) with adstock and saturation	Regression, ROI estimation
2️⃣	02_mmm_fundamentals_tuning.ipynb	MMM fundamentals and adstock tuning	Model fit, parameter search
3️⃣	03_mmm_tree_and_importance.ipynb	Tree-based MMM with feature importance	Random forests, attribution
4️⃣	04_causal_basics_ate.ipynb	Causal inference and treatment effects	Confounding, matching, ATE
5️⃣	05_dml_crossfitting.ipynb	Double Machine Learning (DML) demo	Cross-fitting, causal ML
6️⃣	06_mmm_kpi_viz.ipynb	Visualizing KPIs and correlations	Exploratory data analysis
7️⃣	07_mmm_pitfalls_diagnostics.ipynb	Model diagnostics and pitfalls	Multicollinearity, residuals, VIF
8️⃣	08_attribution_markov.ipynb	Markov-chain attribution	Journey modeling, channel contribution
⚙️ Setup
git clone https://github.com/<your-username>/marketing-data-science-labs.git
cd marketing-data-science-labs
pip install -r requirements.txt


Minimal requirements.txt

numpy
pandas
matplotlib
scikit-learn
statsmodels


Then start Jupyter:

jupyter notebook

 How to Use

Open the notebooks in numerical order (01 → 08).

Run all cells and observe how spend, causality, and attribution are modeled.

Modify parameters to explore:

Different adstock rates and saturation levels

Causal confounding and treatment effects

Feature importances and Markov-chain removal effects

💡 Suggested Extensions

Add budget optimization logic (e.g., gradient or linear solver).

Extend causal models with DoWhy
 or EconML
.

Wrap any notebook into a FastAPI service for real-time simulation.

Visualize attribution paths using networkx or plotly.

References

Marketing Mix Modeling with PyMC – PyMC Marketing Documentation

Causal Inference Tutorial – MIT Economics

Double Machine Learning – Chernozhukov et al.

Storytelling with Data – Cole Nussbaumer Knaflic
