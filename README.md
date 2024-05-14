# Giza X Gora ML Competition: Regression Model
This repository contains the implementation of a regression model trained on the Gora dataset, a lending and borrowing user liquidation history dataset. The model was trained using PyTorch on a selection of relevant features with the goal of achieving high accuracy. The aim of this project is to develop a predictive model that can accurately estimate the liquidation value for lending and borrowing scenarios, with the ultimate goal of competing in the Giza X Gora ML Competition.

the submission file is `submission.csv`. 
just to inform you have to change the evaluation dataset's target value to `np.log1p` because that's what the model is predicting. it is because I want to reduce the influnce of large values in target values.

the model training process is in the `model.ipynb`.

and evaluation on test-set is in `submission.ipynb`.

-* the `test.ipynb` is my intial EDA. nothing to do with model development
