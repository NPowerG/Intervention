# Fibroblast growth factor 21 as a putative Biomarker for behavioural dysfunction in obese mice
@ Created by Dr. Alisha Parveen

# Abstract
Obesity is one of the most challenging diseases of the 21st century and is accompanied by be-havioural disorders. Exercise, dietary adjustments, or time-restricted feeding are the only suc-cessful long-term treatments to date. Fibroblast growth factor 21 (FGF21) plays a key role in di-etary regulation, but FGF21 resistance is prevalent in obesity. The aim of this study was to in-vestigate in obese mice whether weight reduction leads to improved behaviour and whether these behavioural changes are associated with decreased plasma FGF21 levels. After establishing a model for diet-induced obesity, mice were subjected to three different interventions for weight reduction, namely dietary change, treadmill exercise, or time-restricted feeding. In this study, we demonstrated that only the combination of dietary change and treadmill exercise affected all parameters leading to a reduction in weight, fat, and FGF21, as well as less anxious behaviour, higher overall activity, and improved olfactory detection abilities. To investigate the interrela-tionship between FGF21 and behavioural parameters, feature selection algorithms were applied designating FGF21 and body weight as one of five highly weighted features. In conclusion, we concluded from the complementary methods that FGF21 can be considered as a potential biomarker for improved behaviour in obese mice after weight reduction.

# Main task
We aimed to investigate if FGF21 may be considered in this context as a biomarker for be-havioural improvement after weight reduction.

# Workspace
MacOS Big Sur Version 11.2.3:
A CPU was used with specification as following: Intel Core i9 2,4 GHz 8-Core with memory: 64 GB 2667 MHz DDR4.

Microsoft Windows 10 Pro:
A CPU was used with specification as following: Intel(R) Core(TM) i5-4590, 3.30GHz, 3301 MHz with memory: 8 GB.

Linux Ubuntu version 18.04 LTS:
A CPU was used with specification as following: Intel® CoreTM i7-6800K, 3.40GHz x 12 with 62.8GB memory, disk 424.6GB and OS type 64-bit. 

# Platform used
MacOS Big Sur Version 11.2.3
Python 3.8.3 with Spyder 4.2.0 Python IDE

Microsoft Windows 10 Pro and Linux Ubuntu
Python 3.7 with Spyder 4.0.1 Python IDE

# Installation
Python was installed via Anaconda3
https://www.anaconda.com/products/individual


# 1st Task: Stratification from the parent data set
Input: 01_FGF21_parent_dataset.xlsx

Code: 01_data_management.py

Output: 02_Stratified_imputated_data.xlsx

# 2nd Task: Pearson's Correlation and PCA
Input: 02_Stratified_imputated_data.xlsx

Code: 02_PCA_and_Pearson.py

Output: 02_result_PCA_data.xlsx ,
        02_result_Pearson_Correlation_data.xlsx ,
        02_result_PCA_with_index.png ,
        02_result_PCA_without_index.png ,
        02_result_Pearson_Correlation.png 

# 3rd Task: Feature selection
Input: 02_Stratified_imputated_data.xlsx

Code: 03_Feature_selection.py

Output: Console

# 4th Task: Supervised machine learning
non-feature selected data set

Input: 02_Stratified_imputated_data.xlsx

Code: 04_supervised_machine_learning.py

Output: Console


feature selected data set

Input: 04_common_Feature_selection_data.xlsx

Code: 04_supervised_machine_learning.py

Output: Console
