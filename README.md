# LogisticRegression
Projects, performing logistics regression for various clarification and predictive analysis

What is logistic regression?
1. This type of statistical model (also known as logit model) is often used for classification and predictive analytics.
2. Logistic regression estimates the probability of an event occurring, such as voted or didn’t vote, based on a given dataset of independent variables.
3. Since the outcome is a probability, the dependent variable is bounded between 0 and 1. 
4. In logistic regression, a logit transformation is applied on the odds—that is, the probability of success divided by the probability of failure.
5. This is also commonly known as the log odds, or the natural logarithm of odds, and this logistic function is represented by the following formulas:
      5.1 Logit(pi) = 1/(1+ exp(-pi))
      6.ln(pi/(1-pi)) = Beta_0 + Beta_1*X_1 + … + B_k*K_k

Source : https://www.ibm.com/topics/logistic-regression

Understanding Logistic regression:-
In this logistic regression equation, logit(pi) is the dependent or response variable and x is the independent variable. 

The beta parameter, or coefficient, in this model is commonly estimated via maximum likelihood estimation (MLE). 

This method tests different values of beta through multiple iterations to optimize for the best fit of log odds. 

All of these iterations produce the log likelihood function, and logistic regression seeks to maximize this function to find the best parameter estimate. 

Once the optimal coefficient (or coefficients if there is more than one independent variable) is found, the conditional 
probabilities for each observation can be calculated,logged, and summed together to yield a predicted probability. 

For binary classification, a probability less than .5 will predict 0 while a probability greater than 0 will predict 1. 

After the model has been computed, it’s best practice to evaluate the how well the model predicts the dependent variable, which is called goodness of fit. 

The Hosmer–Lemeshow test is a popular method to assess model fit.


---------------------------------------------------------------------------------------------------------

**Types of logistic regression**

There are three types of logistic regression models, which are defined based on categorical response.

**Binary logistic regression:** In this approach, the response or dependent variable is dichotomous in nature—i.e. it has only two possible outcomes (e.g. 0 or 1). Some popular examples of its use include predicting if an e-mail is spam or not spam or if a tumor is malignant or not malignant. Within logistic regression, this is the most commonly used approach, and more generally, it is one of the most common classifiers for binary classification.

**Multinomial logistic regression:** In this type of logistic regression model, the dependent variable has three or more possible outcomes; however, these values have no specified order.  For example, movie studios want to predict what genre of film a moviegoer is likely to see to market films more effectively. A multinomial logistic regression model can help the studio to determine the strength of influence a person's age, gender, and dating status may have on the type of film that they prefer. The studio can then orient an advertising campaign of a specific movie toward a group of people likely to go see it.

**Ordinal logistic regression:** This type of logistic regression model is leveraged when the response variable has three or more possible outcome, but in this case, these values do have a defined order. Examples of ordinal responses include grading scales from A to F or rating scales from 1 to 5. 


---------------------------------------------------------------------------------------------------------------------------------
**Use Cases of Logistics Regression**

**Fraud detection:** Logistic regression models can help teams identify data anomalies, which are predictive of fraud. Certain behaviors or characteristics may have a higher association with fraudulent activities, which is particularly helpful to banking and other financial institutions in protecting their clients. SaaS-based companies have also started to adopt these practices to eliminate fake user accounts from their datasets when conducting data analysis around business performance.

**Disease prediction:** In medicine, this analytics approach can be used to predict the likelihood of disease or illness for a given population.
Healthcare organizations can set up preventative care for individuals that show higher propensity for specific illnesses.

**Churn prediction:** Specific behaviors may be indicative of churn in different functions of an organization. For example, human resources and management teams may want to know if there are high performers within the company who are at risk of leaving the organization; this type of insight can prompt conversations to understand problem areas within the company, such as culture or compensation. Alternatively, the sales organization may want to learn which of their clients are at risk of taking their business elsewhere. This can prompt teams to set up a retention strategy to avoid lost revenue.

-------------------------------------------------------------------------------------------------------------------------------------------
