# Predicting Chess Puzzle Outcomes from Pre-Move EEG: Towards a Human Model of Multi-Step Problem Solving


## Intial data set up

Firstly, please add the "clean_trial_data.pkl", "clean_rest_data.pkl" and "participant_clean_trial_data.pkl" from OneDrive to the Data analysis folder.
Secondly, please unzip "Participant 19.rar" in the Participant Real Data, so that it's directory is the same as other participants. 


## Verifying Package versions

Python: 3.12.10

Please make sure that the packages used are the exact same, since incorrect version can produce silent errors causing errornous results

**[Real_Data_Analyiser]:**

numpy: 2.0.2

pandas: 2.3.3

mne: 1.11.0

matplotlib: 3.10.0

sklearn: 1.8.0

scipy: 1.16.3

lightgbm: 4.6.0

shap: 0.50.0

autoreject: 0.4.3

meegkit: 0.1.9

mRMR: 0.2.8

rpy2: 3.6.3

R packages:

lme4: [1]  1  1 38

lmerTest: [1] 3 2 1

**[ML_analyiser]:**

numpy: 2.0.2

pandas: 2.3.3

mne: 1.11.0

matplotlib: 3.10.0

sklearn: 1.8.0

scipy: 1.16.3

lightgbm: 4.6.0

shap: 0.50.0



## Overview
Overall, the project consists of code (found in the Data analysis folder) and data (found in the Participant Real Data folder). The code is split into two python notebooks; "Real_Data_Analysier.ipynb" which contains the data cleaning + feature extraction pipelines AND "ML_nalysier.ipynb" which contains the machine learning pipeline. The notebooks contain documentation guiding step by step through the code. Other files present in the Data analysis folder are used for saved results and digrams. The notebook explains those files respectively. Please start at "Real_Data_Analysier.ipynb". Side note; "Plot.ipynb" is a small file used for participant statisic plotting. 

