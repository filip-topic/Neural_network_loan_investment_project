# Lending club investment project

The dataset for this project is a Lending Club dataset (in a pkl format).

The main objectives are to build two investment strategies for a potential investor who wants to invest in the lending club platform. 

The first investment strategy is based on maximizing return. In order to do that, we define what return means in this context and how it is calculated. In the dataset, there are five columns named "ret_PESS, ret_OPT, ret_INTa, ret_INTb, ret_INTc". These are some calculated returns based on some definitions, and are not used in the analysis. 

Second investment strategy is based on minimizing default. In order to do this, I create a predictive default model. The aim of this investment strategy is to build a portfolio that achieves the minimum default.

Ultimately, for a given natural number $N$, my methodology comes up with two portfolios made of $N$ loans, one based on the first investment strategy, achieving the highest return, and the other based on the second strategy, achieving the minimum default risk  where I clarify the precise meanings of 'return' and 'default'.

For each investment strategy, I build two predictive models, and of these two models for each investment strategy, one of them is an artificial neural network (ANN).


The structure of the report is as follows:

1) Introduction 

2) Data Exploration 

3) Investment Strategy Based on Return Maximizing

4) Investment Strategy Based on Default Minimization

5) Experiments and Results

6) Conclusions 

7) Acknowledgment

8) References

9) Appendices
