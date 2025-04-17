# CAUSALITY-EXPLORE
MSc Big Data Analytics Final Project

## Project Structure

causality-explorer/
├── 📁 data/                    # All data-related files
│   ├── 📁 raw/                # Untouched original data
│   ├── 📁 interim/            # Cleaned but unprocessed data
│   ├── 📁 processed/          # Feature-ready data
│   └── 📁 external/           # Third-party or synthetic datasets

├── 📁 notebooks/              # Jupyter notebooks for exploration & prototyping
│   ├── 01_data_exploration.ipynb
│   ├── 02_preprocessing.ipynb
│   ├── 03_predictive_modeling.ipynb
│   └── 04_causal_inference.ipynb

├── 📁 src/                    # Main Python package (modular code)
│   ├── __init__.py
│   ├── utils.py              # Common utility functions
│   ├── 📁 data/
│   │   ├── load_data.py
│   │   ├── preprocess.py
│   │   └── feature_engineering.py
│   ├── 📁 models/
│   │   ├── train_predictive.py
│   │   ├── train_causal.py
│   │   └── evaluation.py
│   └── 📁 visualization/
│       └── visual_tools.py

├── 📁 visual_tool/            # Streamlit or Dash MVP app
│   ├── app.py                # Main app entry point
│   └── 📁 components/        # Modular UI components if needed

├── 📁 reports/                # Generated reports, plots, exportables
│   ├── summary.md
│   └── 📁 figures/

├── 📁 configs/                # Configuration files (YAML/JSON)
│   └── model_config.yaml

├── 📁 tests/                  # Unit and integration tests
│   └── test_preprocessing.py

├── README.md                 # Project overview
├── requirements.txt          # Python dependencies
├── environment.yml           # Conda environment setup
└── .gitignore                # Files to ignore in version control
