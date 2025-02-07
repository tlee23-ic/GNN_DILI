## "Improving Drug-Induced Liver Injury Prediction Using Graph Neural Networks with Augmented Graph Features from Molecular Optimisation"

[![DOI:10.26434/chemrxiv-2024-d12gk-v2](http://img.shields.io/badge/DOI-10.26434/chemrxiv.2024.d12gk.v2-F1E518.svg)](https://doi.org/10.26434/chemrxiv-2024-d12gk-v2)

<!--
<p align="center">
    <a href="https://doi.org/10.26434/chemrxiv-2024-d12gk-v2">
        <img src="https://github.com/user-attachments/assets/724f0851-b18a-49cb-99ba-dc151ded3e9e" width="150" alt="DOI Badge" />
    </a>
</p>
-->

<p align="center">
    <img src="https://github.com/user-attachments/assets/3e874068-055b-4387-b05c-971b096e6adc" width="80%" alt="DILIGeNN_original">
</p>


DILIGeNN is a GNN framework that extracts graph features from 3D optimised molecular structures as is done in target-based drug discovery and molecular docking simulation. Our method is the first to encode spatial and electrostatic information into a single graph representation, as opposed to other work that require multiple graphs or additional chemical descriptors for feature representation. Our approach, using warm starts following repeated early stopping during training, outperforms the current state-of-the-art methods in liver toxicity (DILI), permeability (BBBP) and activity (BACE) prediction tasks.

#### DILIGeNN models and results are available for reproducibility
https://zenodo.org/records/14676047

#### DILIGeNN Data Preprocessing.ipynb
Preprocessing algorithm including molecule standardisation, optimisation and custom graph generation in PyTorch
<!--
**Augmented features**: Partial charges / Bond Lengths  
**Updated features**: Atomic / Bond features from the 3D optimized molecules
-->

<p align="center">
    <img src="https://github.com/user-attachments/assets/42712879-0eb2-43ca-82eb-9ba676915b68" width="50%" alt="github1">
</p>


#### DILIGeNN Hyperparameter optimisation.ipynb
Hyperparameter optimisation algorithm for selecting the optimal hyperparameters using grid search

#### DILIGeNN Model Reinit & Fine-tuning.ipynb
Model reinitialisation & sequential warm starts algorithm for fine-tuning DILIGeNN
In this notebook, results are reproduced from the final models saved in https://zenodo.org/records/14676047

#### Bond_analysis.ipynb
Bond length analysis algorithm for standardised and non-standardised molecules.

#### DILIst (2020).xlsx
US Food and Drug Administration (FDA) Drug-Induced Liver Injury Severity and Toxicity (DILIst) Dataset
