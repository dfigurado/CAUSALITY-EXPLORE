# CAUSALITY-EXPLORE
MSc Big Data Analytics Final Project

## Project Structure
causality-explorer/
│
├── data/                      # Raw and processed data
│   ├── raw/                   # Original datasets (GP, synthetic, etc.)
│   ├── interim/               # Cleaned, but not feature-engineered
│   ├── processed/             # Final datasets with features, ready for modeling
│   └── external/              # Any third-party or auxiliary data
│
├── notebooks/                 # Jupyter notebooks for EDA, experiments
│   ├── 01_data_exploration.ipynb
│   ├── 02_preprocessing.ipynb
│   ├── 03_predictive_modeling.ipynb
│   └── 04_causal_inference.ipynb
│
├── src/                       # Source code (modularized scripts)
│   ├── __init__.py
│   ├── data/                  # Scripts to load, clean, engineer features
│   │   ├── load_data.py
│   │   ├── preprocess.py
│   │   └── feature_engineering.py
│   ├── models/                # ML and causal models
│   │   ├── train_predictive.py
│   │   ├── train_causal.py
│   │   └── evaluation.py
│   ├── visualization/         # Plotting and dashboard functions
│   │   └── visual_tools.py
│   └── utils.py               # General utilities (logging, config, etc.)
│
├── reports/                   # Generated results and figures
│   ├── figures/
│   └── summary.md
│
├── visual_tool/               # Code for visual dashboard (e.g. Streamlit/Plotly)
│   ├── app.py
│   └── components/
│
├── configs/                   # YAML or JSON files for configs
│   └── model_config.yaml
│
├── tests/                     # Unit tests for code in `src`
│   └── test_preprocessing.py
│
├── requirements.txt           # Dependencies
├── environment.yml            # (Optional) Conda environment
├── README.md
└── .gitignore
