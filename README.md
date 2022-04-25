##1. Introduce

This is the source code for our paper "A Double-Space and Double-Norm Ensembled Latent Factor
Model for Highly Accurate Web Service QoS Prediction " which contains 8 files, i.e., Ensemble, MF_dot_L1L2, MF_o_L1L2, CommonRecomm, CommonRecomm_dot, CommonRecomm_o, RTuple, and Readme. Among them, Ensemble is the main program, MF_dot_L1L2 and MF_o_L1L2 are two base models respectively.

## 2. Run our algorithm

(1) Download and import files into a JAVA Integrated Development Environment, like “Eclipse”, refer to https://www.eclipse.org/downloads/.

(2) Open “Ensemble.java” and run.

## 3. Parameters setting

Parameters are listed at the main method of “Ensemble.java”. Their meanings are explained as follows:

(1) fileName: the file name of the input dataset which will be initialized in CommonRecomm.initializeRatings().

(2) boolean ifBias: Bias controller. Set true by default to use bias.

(3) int RMSE_OR_MAE: error type. 0 means RMSE, 1 means MAE.

(4) MF_dot_L1L2(double Eta, double Lambda, int RMSE_OR_MAE): Eta means learning rate η, Lambda means regularization parameter λ.

(5) MF_o_L1L2(double Eta, double Lambda, int RMSE_OR_MAE): same as above (4).

## 4. Datasets

The dataset rt5% is provided in the code.
