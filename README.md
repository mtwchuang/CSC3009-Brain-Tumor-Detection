# CSC3009-Brain-Tumor-Detection

## Setting up Project
- Prior to running data_prepreprocessing.ipynb, create folder "prepared_data". Augmented data will be stored and automatically ignored there. 
- For model checkpoints, store them within folder model_checkpoints. Model checkpoints will be stored and automatically ignored there. 
- For model tuning, stored them within folder "kt_tuning". Tuning files will be stored and automatically ignored there. 

## Setting up Python Virtual Environment
Dependencies will be handled through Python's virtualenv. 
```
virtualenv dependencies
```
When using dependencies from IPYNB notebooks in VSCode, click Ctr P, the select Python interpreter as dependencies

Activate the virtual environment from the Terminal
```
./dependencies/Scripts/activate
```
To deactivate the virtual environment
```
deactivate
```