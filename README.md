# UNMR-Net
Original codes for an article titled "UNMR-Net: A Unified Deep Reconstruction Network for Multi-Task Compressed Sensing NMR Spectroscopy".

File “code and model” includes all original code scripts for network architecture, model training, and data reconstruction, in which
“demo_dc” is used to input training dataset;
“train_dc” is used for model training;
“datadc” is used to input undersampled spectrum;
“runn1d_dc” is used to reconstruct 1D simulated data;
“runn2d_dc” is used to reconstruct 2D experimental data.
“istdc_nl12_NUS0.125posong” is well-trained model weights for 12.5% Poisson sparsely sampled 2D protein NMR spectra.

File “results” includes reconstruction results used in the paper, in which
“rec_istdc12_CBDN1_0.125” is used in Figure 2, while results of competing methods remain the same to those in previous paper (https://doi.org/10.1021/acs.analchem.4c04830);
“rec_istdc12_azithromycin_0.125” is used in Figure 3;
“rec_istdc9_quinine_0.161” is used in Figure 4;
“rec_istadc9_vat” is used in Figure 5;

File “testdata” includes test data used in the paper, in which
“CBDN1_dc_0.125posong” is used in Figure 2;
“azithromycin_dc_0.125posong” is used in Figure 3;
“Quinine” is used in Figure 4;
“vat” is used in Figure 5.
If the data was used, please cite the original literatures.

File “training data” includes Matlab code scripts to generate simulated training dataset.
