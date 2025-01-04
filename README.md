# Optiver - Trading at the Close

## Overview

The **Optiver - Trading at the Close** competition focuses on predicting stock price movements during the NASDAQ closing auction. Participants are tasked with using historical auction data and a synthetic index to forecast price changes.

## Repository Structure

### 1. `Exploration.ipynb`
- **Purpose:** Early-stage data exploration and preprocessing.
- **Key Features:**
  - Data chunking for efficient memory usage.
  - Exploratory Data Analysis (EDA) to understand trends and patterns.
  - Data cleaning and wrapper functions.
  - Initial implementation of machine learning models (without GPU acceleration).

### 2. `Experiment_Notebook.ipynb`
- **Purpose:** Advanced model experimentation and optimization.
- **Key Features:**
  - Model training with GPU acceleration (using Google Colab/Kaggle).
  - Selection of optimal models and hyperparameter tuning.
  - Stacking and ensembling to improve performance.

### 3. `requirements.txt`
- **Purpose:** Manage dependencies for the project.
- **Key Features:**
  - List of required Python libraries for running the notebooks.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/optiver-trading-at-close.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset

The dataset is provided by **Optiver** via Kaggle. Download it [here](https://www.kaggle.com/competitions/optiver-trading-at-the-close/data) and place it in the `data/` directory.


## How to Run

1. Open and run `Exploration.ipynb` to explore and preprocess the data.
2. Use `Experiment_Notebook.ipynb` for model training and experimentation.

## Key Contributions

- Comprehensive data cleaning and feature engineering pipeline.
- Innovative stacking techniques to combine model outputs.
- Efficient use of resources with chunking and GPU acceleration.

## Future Work

- Incorporate additional auction-specific features.
- Experiment with advanced deep learning architectures (e.g., Transformer models).
- Optimize the pipeline for faster runtime.

## Contact

For questions or feedback, please contact: ys3748@columbia.edu
