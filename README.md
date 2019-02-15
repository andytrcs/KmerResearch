## Accurate prediction of boundaries of high resolution
Kmer Research in Python and R


The only libraries needed so far is Biostrings. You can install from RStudio or from https://bioconductor.org/biocLite.R

Data: 6mer, 9mer and 12mer motif splitted from fruit fly DNA for TAD prediction.
Link to raw dataset: https://www.ncbi.nlm.nih.gov/gene?Db=gene&Cmd=DetailsSearch&Term=31358


Input: Training csv file and testing csv file can be found in data folder.

Requirement:
R
Caret
e1071
C5.0
Glmnet
Python 3.6
Keras

Model can be found in model folder:
## Master_6mer_file:
## All the feature-based machine learning models:
1. KNN
2. Decision Tree
3. Random Forest
4. Elastic Logistic Regression
5. Boost tree

Metrics recored:
1. Accuracy
2. Sensitivity
3. Specifitivity
4. F1 Score
5. AUC
6. Precision
5. Recall

Result from all models in folder model performance:
KNN	Decision Tree	Boosted Tree	Logistic Regression a=.01	Random Forest
Accuracy	0.815	0.741	0.906	0.67	91.2
Sensitivity	0.942	0.8	0.924	0.662	0.93
Specificity	0.688	0.682	0.888	0.682	0.894
F1 Score	0.8358	0.7554	0.9077	0.6687	0.9136
Precision	0.7512	7156	0.8919	0.6755	0.8977
Recall	0.942	0.8	0.924	0.662	0.93
AUC	0.815	0.7615	0.974	0.72	0.97

## Dense-layer deep learning model:


