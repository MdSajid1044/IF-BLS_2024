Intuitionistic Fuzzy Broad Learning System (IF-BLS)

Please cite the following paper if you use this code in your research.

M. Sajid, A. K. Malik, and M. Tanveer, "Intuitionistic Fuzzy Broad Learning System: Enhancing Robustness Against Noise and Outliers," IEEE Transactions on Fuzzy Systems, vol. 32, no. 8, pp. 4460–4469, Aug. 2024, doi: 10.1109/TFUZZ.2024.3400898.

Paper: https://doi.org/10.1109/TFUZZ.2024.3400898

arXiv Version: https://doi.org/10.48550/arXiv.2307.08713

```
BibTeX
```
@ARTICLE{10530427,
author={Sajid, M. and Malik, A. K. and Tanveer, M.},
journal={IEEE Transactions on Fuzzy Systems},
title={Intuitionistic Fuzzy Broad Learning System: Enhancing Robustness Against Noise and Outliers},
year={2024},
volume={32},
number={8},
pages={4460--4469},
doi={10.1109/TFUZZ.2024.3400898}
}
```
Experimental Setup
```
The experimental procedures are executed on a computing system equipped with MATLAB R2023a, an 11th Gen Intel(R) Core(TM) i7-11700 processor operating at 2.50 GHz with 16.0 GB RAM, running on a Windows 11 operating system.

A demo of the proposed Intuitionistic Fuzzy Broad Learning System (IF-BLS) model is provided using the credit_approval dataset.

Hyperparameter Range

C = [10^{-6}, 10^{-4}, ..., 10^{6}]
m = 1 : 2 : 21
p = 5 : 5 : 50
q = 5 : 10 : 105
mu = [2^{-5}, 2^{-4}, ..., 2^{5}]

The following are the parameters set used for the experiment:

C = 100 (Regularization parameter)
mu = 4 (Kernel parameter)
p = 10 (Number of fuzzy nodes in each group)
m = 1 (Number of fuzzy groups)
q = 85 (Number of enhancement nodes)
```
Description of Files
```
IF_BLS_Main.m
This is the main file to run selected models on datasets. In the path variable, specify the path to the folder containing the codes and datasets on which you wish to run the algorithm.

IF_BLS_Classification.m
This is an intermediate function from which the training and validation functions are called.

IF_BLS_Train.m
This is the training function of the IF-BLS model.

IF_BLS_Validation.m
This is the validation function of the IF-BLS model.

IF_score_fun.m
Implements the intuitionistic fuzzy score function.

credit_approval.mat
Dataset used for demonstration.
```
Note
The codes are optimized for efficiency and have been cleaned for better readability. For detailed experimental settings and theoretical explanations, please refer to the paper.

The codes have been re-run and verified only on a few datasets. If you encounter any bugs or issues, please contact:
M. Sajid (phd2101241003@iiti.ac.in, sajid.mathml@gmail.com
).
```
Acknowledgement
```
Some parts of the codes have been taken from:

C. L. Philip Chen and Zhulin Liu, "Broad Learning System: An Effective and Efficient Incremental Learning System Without the Need for Deep Architecture,"
IEEE Transactions on Neural Networks and Learning Systems, vol. 29, no. 1, pp. 10–24, 2017.
```
13-March-2024
