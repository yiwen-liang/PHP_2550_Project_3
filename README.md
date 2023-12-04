## PHP2550 Project 3: Simulation Studies

### Evaluating the Performance of a Prediction Model in Different Population

${\color{gray}Posted: 12/03/2023}$

This is the 3rd project assignment of PHP2550 Practical Data Analysis course at Brown University (Fall 23).

In this project, our goal is to evaluate the performance of the model constructed on the Framingham dataset in a distinct target population underlying the NHANES data.	The submitted report and the code used for this analysis will be available here. The dataset is not available to the public.

## Documents Available

* *PHP2550_Proejct3_Yiwen_Liang.pdf*: the submitted report of this project assignment.

* *PHP2550_Proejct3_Yiwen_Liang.Rmd*: the code file (.rmd) for this report, including all codes for creating tables, figures and model summaries in the report.

* *brier_est1.RDS*: the simulation results using uniform(1,75) to simualte `AGE`.

* *brier_est2.RDS*: the simulation results using beta(10,19)*100 to simualte `AGE`.

* *brier_est3.RDS*: the simulation results using truncated normal distribution, with lower bound = 1, and upper bound = 75 to simualte `AGE`.

* *project3.R*: the code provided for pre-processing both datasets and constructing the mdoel for evaluation.

## Authors

Yiwen Liang (yiwen_liang@brown.edu)
