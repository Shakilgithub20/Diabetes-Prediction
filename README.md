# Diabetes Prediction using Machine Learning
Statistical models to predict incident are often based on variables, Here, I pursued some main goal. Such as, I train an artificial neural network with dataset and predict the diabetes(Target value of 0/1).
# Details about the dataset:
The datasets consists of several medical predictor variables and one target variable, Outcome.
1) Preg = Number of times pregnant.
2) GLU = Plasma glucose concentration a 2 hours in an oral glucose tolerance test
3) BP = Diastolic blood pressure (mm Hg)
4) ST = Triceps skin fold thickness (mm)
5) INS = 2-Hour serum insulin (mu U/ml)
6) BMI = Body mass index (weight in kg/(height in m)^2)
7) DPF = Diabetes pedigree function
8) Age = Age in years

9) Outcome  = 1 - YES (meaning the patient might Diabetes); 0 - NO (the patient doesn't Diabetes).

Number of Observation Units: 768.

Variable Number: 9
# Parameters
   Activation functions: Sigmoid
   Optimizer: Adam
   No. of Layers: 6 hidden layer & 1 output layer
   Units: 800, 500, 250, 150, 75, 40, 1
   Loss: binary_crossentropy
   Metrics: accuracy
