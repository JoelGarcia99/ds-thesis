# Final job: Data Science 
en: Urban Traffic Prediction using Hybrid Rust-Python Architecture  
es: Predicción de Tráfico Urbano mediante Arquitectura Híbrida Rust-Python  

# Reproduction

For environment constraint export run `conda env export --no-builds > environment.yml`

# Project structure

thesis_project/
├── data/                  # NYC TLC / Ecuador Data
├── src/                   # RUST CODE (Data ingestion/processing)
│   ├── main.rs
│   └── Cargo.toml
├── models/                # PYTHON CODE
│   ├── __init__.py
│   ├── networks.py        # Define your PyTorch GNNs here
│   └── trainer.py         # The training loop logic
├── notebooks/             # JUPYTER
│   ├── 01_data_analysis.ipynb   # Visualizing the raw data
│   └── 02_training_demo.ipynb   # Imports 'models', runs training, plots loss
├── environment.yml        # Your frozen environment
└── README.md
