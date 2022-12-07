# **california-housing-ML**

## <u>**Overview:**</u>
-  For our Project, we have used two regression models to predict the median house value from the California Census 1990 Housing Dataset. For our Linear Regression, we used a linear regression classifier to create a base model to predict the median house value based on the housing attributes. We further attempted to optimize using various regularization techniques. This ultimately did not lead to major improvements from our base model.
                We then attempted a Random Forest Regressor, tuning the max_depth hyperparameter to optimize the model for both accuracy and fit. This was a significant improvement to our base model. For the Logistic Regression, we have utilized a Multinomial logistic regression where we assigned three classes (i.e. 0, 1, 2) to different ranges of the median house value. We have looked at different attributes of the houses in California to predict the three different classifications. The base model had a testing score of 81.46% whereas the training score was 80.91%. To further optimize our models, we have deployed Random Forest Classification and Feature selection with Random Random Forest Classification in an attempt to improve the testing score without compromising too significantly on the training score. With the help of a Random Forest Regressor, we were able to increase our testing score to 85.74%, however, our models started to overfit. In order to reduce the overfitting of our model, we have tried using the Feature Selection which reduced the gap between the testing and training score to a small degree compared to the previous model by 0.40%.



## <u>**Proposal:**</u>
- *Group Number :* 7
- **Topic** : California Housing Data
- *Group Members :*  Loukya Kilari, Sung Ahn, Martin Vasquez, and Eric Button


- *Dataset:* https://www.kaggle.com/datasets/camnugent/california-housing-prices (1.4 MB)

- **Work Breakdown:**
  - Clean and preprocessing of the California dataset
  - Identify and import machine learning library
  - Train and test model
  - Linear Regression
  - Logistic Regression
  - Optimize model
    - <u>Linear Regression</u> : Lasso, Ridge, Elastic Net, Random Forest Regressor
    - <u>Logistic Regression</u> : Random Forest Regressor, Feature Selection with Random Forests
  - Create webpage
  - Summarize results and create visuals
  - Host to GitHub Pages 
- Project Track : <u>_Research_</u>

## <u>**Instructions**</u>

1. `html_files` folder contains all the files related to our website.
1. `Images` folder contains all the images we used for our website and also the graphs we generated from our jupyter notebook.
1. All our jupyter notebooks contain the preprocessing work that we did before running the models.
1. `base_model.ipynb` contains code for our base model.
1. `Logistic_Regression.ipynb` is a jupyter notebook for modeling using logistic regression.
1. `randomforestregressormodel.ipynb` is a jupyter notebook for modeling using random forest regression model.
1. `regularized_regression_models.ipynb` is a jupyter notebook for modeling using linear regression.
1. `README.md` is the file you're currently viewing that summarizes this repo.
1. `housing.csv` contains the dataset that we used for this project.

## <u>**Website for this Repo:**</u>

* https://ericjbutton.github.io/california-housing-ML/  (click on this link to view our website)



