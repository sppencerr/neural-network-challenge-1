# Neural Network Challenge #1 — Student Loan Prediction

This repo contains my solution to a neural network challenge where I built a model to predict whether a student is likely to repay their loan. The goal? Help a fictional loan refinancing company make smarter decisions on interest rates and risk.

##  What's Inside

- `student_loans_with_deep_learning.ipynb`: The main Jupyter notebook — goes through data prep, building and training the model, and making predictions.
- `student-loans.csv`: The dataset provided for the challenge (sourced via URL).

##  What I Did

- Preprocessed the dataset using Pandas and `StandardScaler`
- Built a neural network with TensorFlow and Keras
- Trained it over 50 epochs to predict `credit_ranking`
- Evaluated the model and ran predictions
- Answered a few questions around recommendation systems for student loans

## Notes

- Used ReLU activation for hidden layers, sigmoid for the output layer.
- Binary classification problem with decent balance in the target classes.
- Super basic architecture, 2 hidden layers, nothing wild.

## Final Thoughts

Honestly a fun one. Cool mix of ML, real-world finance problems, and getting hands-on with Keras.  
Might play with more layers or dropout in the future just to see how it performs.