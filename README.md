## "Improving Drug-Induced Liver Injury Prediction Using Graph Neural Networks with Augmented Graph Features from Molecular Optimisation"

<!-- ![Screenshot 2025-02-06 at 7 05 10 PM](https://github.com/user-attachments/assets/724f0851-b18a-49cb-99ba-dc151ded3e9e) -->

<a href="https://doi.org/10.26434/chemrxiv-2024-d12gk-v2">
    <img src="https://github.com/user-attachments/assets/724f0851-b18a-49cb-99ba-dc151ded3e9e" width="150" alt="DOI Badge" />
</a>

![DILIGeNN_original](https://github.com/user-attachments/assets/3e874068-055b-4387-b05c-971b096e6adc)


### DILIGeNN models and results are available for reproducibility
https://zenodo.org/records/14676047

### DILIGeNN Data Preprocessing.ipynb
Preprocessing algorithm including molecule standardisation, optimisation and custom graph generation in PyTorch
![github1](https://github.com/user-attachments/assets/42712879-0eb2-43ca-82eb-9ba676915b68)

### DILIGeNN Hyperparameter optimisation.ipynb
Hyperparameter optimisation algorithm for selecting the optimal hyperparameters using grid search

### DILIGeNN Model Reinit & Fine-tuning.ipynb
Model reinitialisation & sequential warm starts algorithm for fine-tuning DILIGeNN
In this notebook, results are reproduced from the final models saved in https://zenodo.org/records/14676047

### Bond_analysis.ipynb
Bond length analysis algorithm for standardised and non-standardised molecules.

### DILIst (2020).xlsx
US Food and Drug Administration (FDA) Drug-Induced Liver Injury Severity and Toxicity (DILIst) Dataset
