# This Repository is not complete... (update coming soon)
--- 
# Prognosis_of_ICU_Patients_with_EEG_Complexity
Assessed predictive models for ICU patient recovery using various algorithms and EEG complexity-based feature sets.


    - subject_lvl_pipeline.ipynb: an alternative & more involved preprocessing pipline for noisy data. Steps include downsampling, filter, interpolate or remove noisy and non-brain channels, rerefrence, epoch, and finally Independent component anlayis (ICA) to remove noisy compoenents.
    - derivative_project01_setup.ipynb: Coppying data from sourcedata to a seperate derivative file where further anlythis can be done. 
    - derivative_project01/
        - Bulk_Preproc.ipynb
        - 00-Feature Extraction.ipynb (INCOMPLETE CODE): Calculated Various complexy measures with the neurokit2 toolbox. Lempel-ziv complexity (LZc) was calculated with code that was adapted from Schartner et al., 2015 
        - 01-AllComplexityAnalysis.ipynb (INCOMPLETE CODE): 
        - 02-Statistics & sedONvOFF.ipynb (INCOMPLETE CODE): 
        - 03-MachineLearning.ipynb (INCOMPLETE CODE):
        - 04-part2 for all complexity measures.ipynb (INCOMPLETE CODE):