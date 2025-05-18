This project consists of all information required in the execution of the analysis and modelling code 
used for the course work on AI AND SUSTAINABILITY – EEEM073 under the title, "Next-Day Solar Energy Production Forecasting"
Created by: Sanjutha Indrajit (6873815)

Data Link: https://www.kaggle.com/competitions/ams-2014-solar-energy-prediction-contest/data
Personal Project Link (this project can be accessed from this Google Drive folder): 
https://drive.google.com/drive/folders/1_b9kf_kE8bZVDMWuSKTNlsDFbTwB6ziI?usp=sharing

Contents of each folder:

notebooks/
(NOTE: Please run the notebooks in the order indicated by the number in front of the notebook name)
(NOTE: Please replace any hardcoded paths in the notebooks based on whether the notebook is being run on
Google Colab or a local environment)

1_data_preparation.ipynb: Notebook to load the netCDF4  files of the dataset, convert to consumable format for the project and 
                          save the training and testing dataset in csv format

2_data_analysis.ipynb: Notebook that loads the training dataset and performs multicollinearity and correlation analysis on the 
                       parameters

3_modelling_lstm.ipynb: Notebook that contains the LSTM model construction and training code and explainability using SHAP. 
                        This also include testing and performance evaluation code.

4_modelling_stgcn.ipynb: Notebook that contains the STGCN model construction and training code and explainability using 
                         PGExplainer from torch.geometric. This also include testing and performance evaluation code.

5_compression.ipynb: Notebook for compressing the LSTM and STGCN models using two algorithms: dynamic quantisation and distillation.




