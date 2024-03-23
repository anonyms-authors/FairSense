# FairSense

This repo contains the the source code for the paper: Analyzing the Impact of Design Decisions on Long-Term Fairness of ML-Enabled Systems.

### Environment Preparation
Most programs are in python while in predictive policing case study the python main function calls some R functions.

The R version we used is 4.2.3

The python version we used is 3.7. The package environment requirement is in `./requirements.txt`. You can install it using command `pip install requirements.txt` under the repo root folder.

### Simulation source code
The 3 case studies described in the paper are 

1.  Loan lending: `./LoanLending`
2.  Opioid risk prediction: `./`
