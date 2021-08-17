# Pre-Symptomatic-Cognitive-Impairment-Detector-Science-Fair-2021-
The purpose of this project was to test the hypothesis of whether DNA methylation can be used as a biomarker to predict Alzheimer’s disease and to create a method of detecting pre-symptomatic cognitive impairment that is simple, inexpensive, and minimally invasive. This was accomplished through the use of data analysis programs to discover specific CpG site biomarkers from case-control datasets based on probability (p) values and machine learning to create static and progressive models. These models utilize the biomarkers to distinguish mild cognitive impairment patients from controls as well as predict one’s status (No Disease, Mild Cognitive Impairment, Alzheimer’s Disease) in two years based on their current status respectively. Hundreds of sites with a p-value under 1E-5 from the GSE156984, GSE153712, and ADNI datasets were found to be significant regarding the development of Alzheimer’s. These sites were then used along with machine learning algorithms to create the static and progressive models. The best static model utilized 300 sites (GSE156984, GSE153712) found using the lasso algorithm and the SVC algorithm, with a testing accuracy of 80.3%. Furthermore, the ND to MCI conversion progressive model built using 79 sites (ADNI) and SVC had a testing accuracy of 86.1% while the MCI to AD conversion model which used 80 sites (ADNI) and SVC had a testing accuracy of 90.9%. In conclusion, it can be reasonably assumed that the hypothesis regarding the feasibility of using DNA methylation as a biomarker to predict Alzheimer’s disease was supported.
