# Bayesian Neural Network Predictions for Fermi-LAT UNID Sources as DM subhalos

In this repository we make the Bayesian neural network predictions for the Fermi-LAT 4GFL-DR3[1] publicly available. As outlined in ArXiv:2301.XXXXX [2], we have built a simulation setup for dark matter subhalos with different models and used these and classified 4FGL sources to train a Bayesian neural network to classify yet unidentified gamma-ray sources (UNIDs). The resulting predictions are tabulated for each model in the file UNID_predictions.csv.

For each UNID source in the 4FGL-DR3 catalog, we provide the prediction mean and standard deviation of each source to belong to each of the five models discussed in the paper (m_DM = [10, 30, 80, 300, 1000] GeV). 

All predictions and the respective standard deviations < 1 % are set to 0. Also, all sources that are cut from the consideration as subhols (see [2] for details) only contain 0 entries. 

[1] LAT Collaboration, S. Abdollahi, F. Acero, L. Baldini, J. Ballet, D. Bastieri et al., 
    Incremental fermi large area telescope fourth source catalog, 2022. 
    DOI:10.3847/1538-4365/ac6751
    Arxiv:2201.11184

[2] Cite our paper
