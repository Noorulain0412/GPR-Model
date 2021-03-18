# GPR-Model
This model is used to assess lightning-induced over-voltages considering various influential parameters such as ground resistivity, ground permittivity, return stroke velocity, return stroke peak current, front time, and distance of lightning channel from overhead line.

Step 1: Import 'trainedModel.mat' in MATLAB 

Step 2: Now import 'T.xlx' in MATLAB (random test case where different columns represent features of the trained model)

Step 3: Type 'yfit=trainedModel.predictFcn(T)' on command prompt of MATLAB

Step 4: The predicted peak values of lightning-induced overvoltages will be displayed on command prompt for the given test data (you can change the test data according to your requirements in T.xlx file)

An example has been demonstrated using the test case data (T). The predicted LIVs corresponding to T have been shown in predicted data (P). A comparison of LIVs predicted from model and FDTD has been provided also. 
