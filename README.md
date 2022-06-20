# Templates for Data Science and Machine Learning -Trainee

The objective of this repository is to make available basic templates for any Machine Learnig and Data Science (Trainee) project in Python.



For any Machine Learning project, we have a Roadmap that in most cases is always respected with some variations:

✅ 1) Raising the question ❓
✅ 2) Acquiring the data 🔍
✅ 3) Adapting information, identifying and correcting anomalies 🔧
✅ 4) Preparing data for training and testing 🏃♂️
✅ 5) Training the model with training data🏋️♀️
✅ 6) Making predictions with test data 🤔
✅ 7) Comparing predictions with test data📝
✅ 8) Adjusting the model🔨
✅ 9) Submitting results 🌟

Then, the repository consists of creating a series of templetates as automated as possible for each stage of the analysis. Unused libraries and functions should be removed so that the program is not overloaded. But to summarize the steps:

1) **Raising the question:** Clearly state what the features are, what type they are, what is our target and what is the result we want to achieve. Based on this we already have a clear objective.

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

The percentage criteria must be chosen by each developer, by default it will be set at 0.2.


The idea is to add linear regression, clustering and recommender systems in the future. So far the only thing developed is a template for categorical variables. Through SK Learn, with the cross validation and grid search method, the following models are being created

The models are as follows:

Depending on the target variable we have to predict, we have:

v1.0.0


## Logistic Regression.
-------------------------------------------------------------

* Linear Discriminant Analysis (LDA).
* KNearest Neighbors
* MLP Classifier
* Decision Tree Classifier
* Random Forest Classification
* Support Vector Classifier
* Gradient Boosting Classifier















## License

See the [LICENSE](LICENSE) file for license rights and limitations (GNU).
