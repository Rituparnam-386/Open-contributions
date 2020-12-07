# Machine learning algorithms

# 1.Supervised learning algorithm (TASK DRIVEN)-
Predictive model as the name suggests is used to predict the future outcome based on the historical data. Predictive models are normally given clear instructions right from the beginning as in what needs to be learnt and how it needs to be learnt. These class of learning algorithms are termed as Supervised Learning.
 Ex-email spam classification
Types of Supervised algorithm –
1.Classiication

2.Regression

Classification algorithms such as-

1.Naive Bayes- features independent contribute to predict the future occurances of events.
example-sentimental analysis

2.Svm-The algorithm divides the data points into classes to find a maximum marginal hyperplane.
Example-Text recognition.
3.KNN- a lazy learning algorithm ,storing instances of training data.
Example-Stock analysis

4.Decision tree-classifies the features on given condition  in form of tree structure.
Example-fraud detection.

5.Ramdom forest etc.

Disadvntage-
1.It requires a lot of training data 

2. The process  takes time.

 # 2. Unsupervised learning algorithm(DATA DRIVEN)-
 The algorithm where dataset is provided but no data is label ,the data labels need to find out by studying the patterns and behavior of different data parameters  or features such class of algorithm  is known as Unsupervised Algorithm.

Types of  unsupervised learning –

Clustering-  Categorizes and group similar data points which is unlabeled we need to measure similarity measures.
Example-Customer segmentation

#3.Reinforcement learning(learns in an environment)-The agent  learns to achieve a goal  in a environment in its present state and learns and gain reward here no dataset is given.

## Evaluation metrices-

Performance measure taken in order to evaluate the model such as confusion matrix to estimate the truly positive and truly negative values in the dataset and to take measures to evaluate the respective parameters such categorical variables and ordinal variables.

Precision-  To judge the precision value and occurences of true positive data.

Recall –  When the data has false positive data more,lower will be its recall.

## Regression algorithm-
Regression analysis  is a supervised algorithm technique used to judge the relationship between a dependent and  independent variable.

## Linear regression-    
The output is dependent  upon the one independent  feature .
It  attempts to indicate the link between the 2 variable,input(X) & output(Y) with the equation.
The Input variable is called the Independent Variable and the Output variable is called the Dependent Variable.
When unseen data is passed to the algorithm, it uses the function, calculates and maps the input to a continuous value for the output.


The equation has the form Y= B0 + B1X, where Y is the dependent variable 
                                                                  X is the independent variable 
                                    B0 is the slope of the line and
                                   B1 is the y-intercept.

Example- house price prediction



## Logistic regression – 
The algorithm where  the  output depends upon the set of independent features and to predict the dependent variable. It can be used for Classification as well as for Regression problems, but mainly used for Classification problems.
Logistic regression is used to predict the categorical dependent variable with the help of independent variables.The output of Logistic Regression problem can be only between the 0 and 1.
Logistic regression can be used where the probabilities between two classes is required.

The equation has the shape –

log(Y/1-Y)=B0+B1X1+B2X2+....,where Y is that the variable
                               X is that the variable quantity (i.e. it's plotted on the X axis).
The output curve is understood as Sigmoid 'S' Curve. 

Example- classify whether the tissue is  malignant or benign
