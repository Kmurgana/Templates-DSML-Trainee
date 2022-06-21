# Templates for Data Science and Machine Learning -Trainee

## Modules
[[Intro](#intro)]
[[General](#general)]
[[Steps](#steps)]
[[Classification_Template](#classification_template)]
[[License](#license)]


## Intro

* The objective of this repository is to make available basic templates for any Machine Learnig and Data Science (Trainee) project in Python.
* Then, the project consists on creating a series of templetates as automated as possible for each stage of the analysis, including the stage of model training, predictions and delivery of the final result.
* This repository is created by a **Trainee and totally new to Data Science**, my apologies if there are misconceptions and/or criteria.

## General

For any Machine Learning project, we have a Roadmap that in most cases is always respected with some variations:

 1) Raising the question ❓
 2) Acquiring the data 🔍
 3) Adapting information, identifying and correcting anomalies 🔧
 4) Preparing data for training and testing 🏃
 5) Training the model with training data🏋️
 6) Making predictions with test data 🤔
 7) Comparing predictions with test data📝
 8) Adjusting the model🔨
 9) Submitting results 🌟

## Steps 

1) **Raising the question:** ❓ Clearly state what the features are, what type they are, what is our target and what is the result we want to achieve. Based on this we already have a clear objective.

2) **Acquiring the data**: Obtaining the variables from all the sources where they come from, in pdf, json, csv, excel, dot, etc. At this stage a small check is made with head() and shape **nothing else**.

3) **Adapting information, identifying and correcting anomalies**: If we have many data sets, adapt all of them to a single standardized format, then concatenate them seamlessly, after that, pass all data through a filter to detect, anomalies, missing information, outliers, etc. 
-Once all anomalies are detected, at this stage they are also corrected as appropriate (it is up to the person to determine the importance or not of the outliers as well as the anomalies).

4) **Preparing data for training and testing**: in this step, we will decide what will be the best way of standardization for the data, according to the type of information, variables, etc. We have:
* One - Hot Encoding
* Frequency coding
* Standard scaling 
* Maximum and minimum scaling (0 - 1)
* Normalization

Once the variables have been normalized, the data must be separated between training and testing:

* X_train, X_test
* y_train, y_test

The percentage criteria must be chosen by each developer, by default it will be set at **0.2**.

5) **Training the model with training data:** We choose the predictive models that best fit (this depends on the developer's knowledge), train the models and choose the one whose hyperparameters and results are most suitable for what we are looking for.

6) **Making predictions with test data*: Once we have our model chosen and trained with our testing set, we input the testing set in order to make predictions with a lower fraction and compare results going forward.

7) **Compare predictions with test data**: In this section we contrast the predictions of the testing set with the y_test, depending on which is the result we can see if the model has overfitting or underfitting for which we can readjust it if required.

8) **Adjust the model**: According to the results obtained in 7) we should evaluate if the model needs adjustments or not, this step can be skipped if we are satisfied with the results obtained in 7), otherwise, we can train another model or change the hyperparameter that we believe convenient.


9) **Present the results:** Finally, once we have our chosen model and we are satisfied with the result, the final predictions are made if there are any with the data set without a target, and the results are saved according to those requested or according to our criteria.


Current version v1.0.0


**Training the model with training data:

## Classification_Template
-------------------------------------------------------------

The idea is to add linear regression, clustering and recommender systems in the future. So far the only thing developed is a template for categorical variables. Through SK Learn, with the cross validation and grid search method, the following models are being created

The models are as follows:

Depending on the target variable we have to predict, we have:

* Linear Discriminant Analysis (LDA).
* KNearest Neighbors
* MLP Classifier
* Decision Tree Classifier
* Random Forest Classification
* Support Vector Classifier
* Gradient Boosting Classifier

----------------------------------------------------------
## License

See the [LICENSE](LICENSE) file for license rights and limitations (GNU).

## 💻 Built with

- [Python](https://python.org/): for programming language.
- [Jupyter Notebook](https://jupyter.org/): as IDE for runing the programm.

<hr>
<p align="center">
Developed with ❤️ in Argentina 🇮🇳 
</p>
