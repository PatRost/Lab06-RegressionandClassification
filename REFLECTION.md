# Lab 06 — Regression and Classification
## Group 4 — Reflection Journal

**Course:** ITAI 1371 — Introduction to Machine Learning  
**Lab:** Module 06 — Regression and Classification Models

---

### Member 1 — Patrick Rostand Gandjouon Tchassem

This lab helped me understand the difference between regression and classification and how both are used in machine learning. Before completing the lab, I knew that machine learning models could make predictions, but I did not fully understand why different problems require different models. Working with the Titanic dataset helped me see that Linear Regression predicts numerical values, such as passenger fares, while Logistic Regression predicts categories, such as whether a passenger survived.

One thing I found interesting was how we used the same dataset to solve two different problems. For Linear Regression, I used Age and Pclass to predict fares, and the model produced a Mean Squared Error of 3364.92. For Logistic Regression, I used Age, Pclass, and Sex to predict survival, and the model achieved 74.83% accuracy. These results helped me understand that each model needs a different way of measuring performance.

I also learned that getting a result does not always mean a model is perfect. The regression model still had prediction errors, and the classification model did not predict every passenger's survival correctly. This lab helped me better understand the steps of preparing data, training models, making predictions, and evaluating results. I feel more comfortable working with supervised learning and would like to learn how to improve model accuracy in future labs.

---

### Member 2 — Kenneth Kouokam

For Module 06, my role focuses on data preparation and train/test splits. The main idea I take from
this section is that a model needs more than a dataset to begin learning. We have to decide what
information it should use, what it should predict, and how we will check its performance. These
decisions shape the meaning of the results. A model can run successfully, but its evaluation is only
useful if the data has been organized in a way that matches the problem.

The two prediction tasks help me understand the difference between features and targets. For fare
prediction, Age and Pclass provide the information, while Fare is the value we want to estimate. For
survival prediction, Sex is added to the inputs and Survived becomes the target. Using the same
dataset for two different questions makes this distinction clearer to me. The dataset itself does not
determine whether the task is regression or classification; the kind of answer we want to predict does.

The handling of missing ages also connects this lab to Module 05. That lab introduced filling missing
ages with the median, while this notebook removes rows with missing Age values for simplicity. This
comparison shows me that preparation involves choices rather than one rule that always works.
Removing rows avoids guessing an age, but it also removes passengers from the analysis. A
question I would want to explore is whether those excluded passengers differ from the ones we keep
and how that could affect the results.

The train/test split is especially important because learning and evaluation serve different purposes. I
think of the training data as practice examples and the test data as a separate check. If the model
were evaluated only on the examples it learned from, the score could give an overly positive
impression of how well it handles new passengers. The 80/20 split keeps some examples aside for
this check. Setting random_state=42 makes that split repeatable, but it does not automatically make
the model more accurate.

Encoding Sex is another reminder that the meaning of a column matters as much as its format. The
values 0 and 1 represent two categories, not a ranking. My main takeaway is that preparation
decisions need explanations, even when the code is short. In my part of the group work, I want to
make the connection between the original data and the model inputs clear. Understanding that
connection helps me judge what an evaluation score can tell us and what it cannot establish on its
own.

---

### Member 3 — Saimi Manasiya

In this lab, I learned how to interpret machine learning models and understand the differences between regression and classification. I learned that regression is used to predict continuous numerical values, such as passenger fares, while classification is used to predict categories, such as whether a passenger survived or did not survive. I also learned how to print and interpret the coefficients of a Linear Regression model using lr_model.coef_. These coefficients help explain how features such as Age and Pclass influence the predicted fare, while keeping the order of the features in mind. Additionally, I understood why Mean Squared Error (MSE) is suitable for evaluating fare predictions and why accuracy is appropriate for evaluating survival classification. This activity helped me understand how to interpret model results instead of only focusing on writing code. Overall, I improved my understanding of machine learning concepts, model evaluation, and the importance of choosing the correct evaluation metric for different prediction problems.

### Member 4 — [Full Name]

**Reflection:**

[Write your personal reflection here.]

---

### Member 5 — [Full Name]

**Reflection:**

[Write your personal reflection here.]
