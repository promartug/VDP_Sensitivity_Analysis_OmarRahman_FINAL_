# AMATH 445 Final Project: 129Xe MRI VDP Sensitivity Analysis

Code and data evaluating the sensitivity of Ventilation Defect Percent (VDP) computations in hyperpolarized 129Xe MRI pipelines. It compares unsupervised clustering (K-Means, GMM, Hierarchical) against supervised baselines (Logistic Regression, MLP) across different cluster counts, masking strategies, and bootstrap resamples.

## Files
* **`OmarRahman_AMATH445_code_FINAL_Project.ipynb`**: Main Jupyter notebook containing the full pipeline, experiments, and figure generation.
* **`Xe vs 19F processing code and data.zip`**: Raw MRI dataset and preprocessing scripts.
* **`DeepLearning_Code_Aug_19_2024_efsremoved.zip`**: Code and data for the supervised baseline experiments.

## Setup
**Requirements:** `numpy`, `scipy`, `matplotlib`, `scikit-learn`, `torch`.

1. Extract the `.zip` archives into the root directory.
2. Open the notebook and update directory paths to match the extracted folders.
3. Run sequentially to reproduce all VDP calculations, spatial maps, and bootstrap distributions used in the final report.

**Author:** Omar Rahman
