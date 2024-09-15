# AutoFlow: An Autoencoder-based Approach for IP Flow Record Compression

This repository contains all the digital artifacts associated with the paper **"AutoFlow: An Autoencoder-based Approach for IP Flow Record Compression with Minimal Impact on Traffic Classification."**

## Repository Structure

### 1. **[VanillaAE](VanillaAE.ipynb)** 
This Jupyter Notebook contains all resources related to the **Vanilla Autoencoder** used in the paper. It includes the entire workflow:

- **Data Preprocessing:** Includes steps like outlier removal and robust scaling.
- **Autoencoder Architecture:** Details of the Vanilla Autoencoder model used for IP flow record compression.
- **Training Process:** Training configuration, loss function, optimizer, and training duration.
- **Results Analysis:** Contains visualizations and metrics for model performance.

### 2. **[VanillaAEvsDAE](VanillaAEvsDAE.ipynb)**
This Jupyter Notebook provides a comparative analysis between the **Vanilla Autoencoder** and the **Denoising Autoencoder (DAE)**:

## How to Use

1. **Run the Jupyter Notebook:** Open `VanillaAE.ipynb` to reproduce the experiments and results related to the Vanilla Autoencoder.
2. **Model Comparisons:** Check `VanillaAEvsDAE.ipynb` for the comparison between Vanilla AE and Denoising AE.
   
