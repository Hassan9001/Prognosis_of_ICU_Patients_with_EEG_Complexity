# This Repository is not complete...
# Update Coming Soon!
--- 
# Prognosis_of_ICU_Patients_with_EEG_Complexity
Assessed predictive models for ICU patient recovery using various algorithms and EEG complexity-based feature sets.


    - derivative_project00/preproc: an alternative & more involved preprocessing pipline for noisy data. Steps include downsampling, filter, interpolate or remove noisy and non-brain channels, rerefrence, epoch, and finally Independent component anlayis (ICA).
    - Derivative_project01_dataprep: Prepping data from sourcedata to be used in a sep derivative file. 
    - derivative_project01/00-Feature Extraction: Calculated Various complexy measures with the neurokit2 toolbox. However, Lempel-ziv complexity (LZc) was calculated usingcode that was adapted from Schartner et al., 2015
