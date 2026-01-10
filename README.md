# Glioblastoma scRNA-seq Analysis (Couturier 2020)

This repository contains the analysis of single-cell RNA sequencing data from Glioblastoma Multiforme (GBM) samples, based on the dataset provided by Couturier et al. (2020).

## Project Structure

- `scRNA-seq_GBM_3CA.ipynb`: Main analysis notebook.
- `Data_Couturier2020_Brain/`: Directory containing the raw data files.
  - `Exp_data_TPM.mtx`: Gene expression matrix (TPM).
  - `Cells.csv`: Cell metadata.
  - `Genes.txt`: Gene names.
  - `Samples.csv`: Sample information.

## Dependencies

The analysis requires Python and the following libraries:

- scanpy
- pandas
- numpy
- matplotlib
- seaborn
- scipy

You can install the dependencies using pip:

```bash
pip install -r requirements.txt
```

## Usage

1. Ensure you have the data files in the `Data_Couturier2020_Brain` directory.
2. Install the required dependencies.
3. Open `scRNA-seq_GBM_3CA.ipynb` in Jupyter Notebook or JupyterLab.
4. Run the cells to reproduce the analysis.

## Data Source

The data used in this analysis is from the study:
*Couturier, C. P., et al. (2020). Single-cell RNA-seq reveals that glioblastoma recapitulates a normal neurodevelopmental hierarchy. Nature Communications, 11(1), 3406.*
