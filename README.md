# Female Pregnancy Outcome

## Project Objectives

This project aims to predict the outcome of pregnancy in a woman using the AHS dataset and the decision tree algorithm. The objective is to develop a model that can accurately predict the risk of adverse pregnancy outcomes, such as preterm birth, low birth weight, and gestational diabetes. The decision tree algorithm will be used to build a classification model that can identify the most important predictors of adverse pregnancy outcomes. The model will be trained and evaluated using historical data from the AHS dataset.

## Project Structure
<!-- - `assets/` - Holds plot images obtained during the study. -->
- `datasets/` - Holds the dataset used in the study.
<!-- - `production/` - Holds Django files that enables prediction in a live environment
- `production/artifcats/` - Holds contents of the compiled model.
- `production/templates` - Holds html files used in the web environment.
- `production/static` - Holds CSS files used in the web environment.
- `production/RequestHandler` - Holds files that interface with the prediction functions. -->

### Installing dependencies
The following packages are required to run the notebook:

- pandas
- matplotlib
- sklearn
- keras

You can install all of the required packages by running the following command in your terminal:

```sh
pip install -r requirements.txt
```

## Collecting metrics
The performance of each model was evaluated using the R2 Score metric. The higher the score, the better the model's performance.

## Conclusion
Overall, the best model for predicting the pregnancy outcome te was the Decision Tree Classifier with an accuracy score of 98%
