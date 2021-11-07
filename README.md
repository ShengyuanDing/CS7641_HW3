# CS7641_HW3
This is the project for CS7641 HW3. 
1. Environment to run the code.
python version: 3.9.4
all the packages required for this project are in requirement.txt
use the following command to install all the required packages:
pip install -r requirements.txt

2. Structure of the project

three folders under  folder CS7641_HW3:
data/
	breast_cancer_dataset.csv
	ovarian_cancer_dataset.csv
scripts/
	Clustering and Dimensionality Reduction on Breast Cancer and Ovarian Cancer dataset.ipynb
	Run Neural Network with dimensionality reduction.ipynb

results/
	ann_breast_cancer_dt.txt
	ann_breast_cancer_em.txt
	ann_breast_cancer_ica.txt
	ann_breast_cancer_km.txt
	ann_breast_cancer_pca.txt
	ann_breast_cancer_rp.txt
	ann_breast_cancer_summary.txt

3. How to run the script
1)install the packages required for this project using above mentioned command.
2)install jupyter notebook
3)open the Clustering and Dimensionality Reduction on Breast Cancer and Ovarian Cancer dataset.ipynb under the folder of scripts in jupyter notebook.
This file is to analyze how to select optimal number of clusters for K-means clustering and EM clustering, and how to select optimal components for 
dimensionality reduction algorithms. The results of KM and EM clustering with and without dimensionality reduction were also produced by this file.
open the Run Neural Network with dimensionality reduction.ipynb.
In this file, different dimensionality reduction algorithms were applied to the Breast Cancer dataset and the Neural Network learner was rerun on the
newly projected data. Also, the results of clustering of KM and EM were added as new features of the Breast Cancer dataset,  the dimesionality reduction
algoriths were applied to the dataset, and the the Neural Network learner was rerun.
4)the results of rerun the Neural Network learner were save under the folder results.

Note: the data were loaded using the relative path. If you change the structure of the project,
please change the relative path to read the csv files respectively. It took several hours to 
run the script since genetic algorithm needs a long time to converge when optimizing weights
of the neural network.

Link to github:

https://github.com/ShengyuanDing/CS7641_HW3.git