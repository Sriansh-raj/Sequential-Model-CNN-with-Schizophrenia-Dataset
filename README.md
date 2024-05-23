# Sequential-Model-CNN-with-Schizophrenia-Dataset

This repository contains the python notebook, in which 1D CNN (Sequential Model) has been implemented on a publicly available schizophrenia dataset. The dataset can be found in the [RepOD website.](https://repod.icm.edu.pl/dataset.xhtml?persistentId=doi:10.18150/repod.0107441) 

## Dataset Description
The dataset comprised 14 patients with paranoid schizophrenia and 14 healthy controls. Data were acquired with the sampling frequency of 250 Hz using the standard 10-20 EEG montage with 19 EEG channels: Fp1, Fp2, F7, F3, Fz, F4, F8, T3, C3, Cz, C4, T4, T5, P3, Pz, P4, T6, O1, O2. The reference electrode was placed between electrodes Fz and Cz.

## Work Description
- All the required libraries have been imported. (numpy, pandas, matplotlib, glob, scipy, tensorflow-keras, scikit-learn)
- Used Python MNE to read `.edf` files.
- labels and group has been created.
- Extracted features. (12 features used)
- Applied sequential model (9 layers) & used `LeakyReLU` activation function.
- Trained model with 15 epochs and 400 batch size.
- Achieved 71.5 % accuracy.
