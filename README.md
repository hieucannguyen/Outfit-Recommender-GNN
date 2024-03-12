# Outfit-Recommender-GNN

## Data Source

https://github.com/AemikaChow/AiDLab-fAshIon-Data

## Sample Directory

```
outfit-recommendation-project/
│
├── data/
│   ├── raw/                  # Store raw data, such as the Polyvore dataset
│   ├── processed/            # Processed and cleaned data ready for modeling
│   └── embeddings/           # Generated embeddings for clothing items
│
├── models/
│   ├── inception_v3/         # Pre-trained InceptionV3 model for feature extraction
│   ├── graphSAGE/            # GraphSAGE model files and training checkpoints
│   └── mlp_classifier/       # Multi-layer perceptron classifier model files
│
├── notebooks/
│   ├── data_preparation.ipynb   # Notebooks for data cleaning and preparation
│   ├── feature_extraction.ipynb # Notebooks for extracting features from images
│   ├── graph_construction.ipynb # Notebooks for constructing the outfit graph
│   └── model_training.ipynb     # Notebooks for training and evaluating models
│
├── src/
│   ├── data_processing/      # Scripts for data cleaning and preprocessing
│   │   ├── clean_data.py
│   │   └── split_data.py
│   │
│   ├── feature_extraction/   # Scripts for extracting features using InceptionV3
│   │   └── extract_features.py
│   │
│   ├── graph_construction/   # Scripts for constructing the graph representation
│   │   └── build_graph.py
│   │
│   ├── embeddings/           # Scripts for generating embeddings using GraphSAGE
│   │   └── generate_embeddings.py
│   │
│   └── model/                # Scripts for model definition, training, and evaluation
│       ├── graphSAGE_model.py
│       ├── mlp_classifier.py
│       └── train_evaluate.py
│
├── results/
│   ├── plots/                # Plots and figures for analysis and evaluation
│   └── performance_metrics/  # Stored metrics and evaluation results
│
├── docs/
│   ├── project_report.md     # Project report or documentation
│   └── setup_instructions.md # Instructions for setting up and running the project
│
└── requirements.txt          # Project dependencies and libraries
```
