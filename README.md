# AutoFlow: An Autoencoder-based Approach for IP Flow Record Compression

This repository contains all the digital artifacts associated with the paper **"AutoFlow: An Autoencoder-based Approach for IP Flow Record Compression with Minimal Impact on Traffic Classification."**

## Dataset

The dataset used in this work is available in the [IFLforTFC repository](https://github.com/FlowFrontiers/IFLforTFC). The notebook will automatically download it, but you can also obtain it manually:

- **Direct link:** [dataset.parquet](https://github.com/FlowFrontiers/IFLforTFC/raw/main/datasets/dataset.parquet)
- **Contents:** 3,163,462 IP flow records with 72 features and application labels for 10 traffic classes

## Repository Structure

### 1. **[VanillaAE](VanillaAE.ipynb)**
This Jupyter Notebook contains all resources related to the **Vanilla Autoencoder** used in the paper. It includes the entire workflow:

- **Data Preprocessing:** Includes steps like outlier removal and robust scaling.
- **Autoencoder Architecture:** Details of the Vanilla Autoencoder model used for IP flow record compression.
- **Training Process:** Training configuration, loss function, optimizer, and training duration.
- **Results Analysis:** Contains visualizations and metrics for model performance.

### 2. **[VanillaAEvsDAE](VanillaAEvsDAE.ipynb)**
This Jupyter Notebook provides a comparative analysis between the **Vanilla Autoencoder** and the **Denoising Autoencoder (DAE)**.

## How to Use

1. **Install dependencies:** `pip install torch scikit-learn pandas numpy matplotlib seaborn scipy joblib requests`
2. **Run [VanillaAE.ipynb](VanillaAE.ipynb):** Downloads the dataset and reproduces all experiments and results from the paper.
3. **Run [VanillaAEvsDAE.ipynb](VanillaAEvsDAE.ipynb):** Comparative analysis between Vanilla AE and Denoising AE. Requires `dataset.parquet` (produced by step 2).

Both notebooks include pre-computed cell outputs matching the final results reported in the paper.
