## How to reproduce the results?
- The dataset can be downloaded as a zipped file from https://zenodo.org/records/1280684
- Firstly, the Conda environment that was used for the analysis is provided as a .yaml file ('neonatal_EEG_analysis_env'). Uploading this environment in Anaconda Navigator will take care of necessary libraries/dependencies required for the analysis. After accessing the environment one can execute the Experiments 1-3.
- Each experiment folder consists of three jupyter notebook which need to be run in the sequence 1) Preprocessing_of_edf_files.ipynb 2) EEG_data_analysis_and_visulaization.ipynb and 3) Attention_based_classification.ipynb; Of course the file path to the dataset needs to be adjusted.
- For Experiment 3 in notebooks 2 and 3 you can put the desired_doctor to be 'A', 'B' or 'C' to run the experiemnt as per the annotations of a particular doctor.
