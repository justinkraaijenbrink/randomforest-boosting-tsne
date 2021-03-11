# randomforest-boosting-tsne
Report and corresponding Python code for an assignment on recommender systems for the course Advances in Data Mining at Leiden University. The project has been carried out together with Freek van Geffen.

The documents included in this repository:

1. The actual assignment
2. A written report
3. Several Python code files
4. Data files

Results presented in report.pdf can be reproduced by running the files A3_RandomForest, A3_Boosting and 
A3_Visualizations in Jupyter Notebook. Data that was used to run the analyses is contained in the folder
'data':
	- Housing.csv (regression)
	- PAM50_proteins (classification)
	- clinical_data_breast_cancer.csv (classification)
	- 77_cancer_proteomes_CPTAC_itraq.csv (classification)

These datafiles were obtained from https://www.kaggle.com/ashydv/housing-price-prediction-linear-regression/data?select=Housing.csv
(regression) and from https://www.kaggle.com/piotrgrabo/breastcancerproteomes (classification).
Note that the correct filepath must be specified, otherwise the data can't be loaded into memory. When the notebook is opened
from the folder, this should be done automatically.

WARNING: the runtime of the entire notebook may take quite a while, since there are some complex algorithms involved. 

Best regards,
Freek and Justin
