# Parkinson-AI

The aim of this project was to create a deep learning classifier capable of diagnosing Parkinson's disease based on an audio recording of the patient. 

### Contents:
1. Folders:
    * csvs - Directory containing csv files with extracted features for each fearture set for both split and whole files
    * full_model_testing - Directory containing both csv files with training parameters and exported models for each fold trained with the newest model version
    * layer_test_train_outputs - Directory with csv files containing training parameters of multiple tested deep layer architectures
    * Test sripts - Directory containing test script, not used in final project
    * train_outputs - Directory containing csv files with training parameters for the first model version

2. Files:
    * basic_model - First version of the model, without KFold and not utilising the best architecture
    * data_praeparation - Functions and script used to split samples and extract features
    * model_v1 - Second version model, uses KFold but not the best architecture
    * model_full - Latest version of the model
    * model-Layers-Testing - model version used to test deep layer architectures
    * visualize_results - file containing training parameter visualization and model comparison
