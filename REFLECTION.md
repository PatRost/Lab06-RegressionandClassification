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

### Member 4 — Anavictoria Cavazos

Reflection

After completing Module 06 and reflecting on the learning I acquired from it, I would say with honesty that this module showed me more 
about errors than the actual concepts involved, but to clarify I did learn from the concepts and task themselves. In my reflection I will 
center my point of view or learning in errors because when working on 06 I experienced about 10 minutes worth of error and trying to fix 
it. Now, how exactly did this happened or why did I spent 10 minutes with an error? Well the response is simple just as the problem was, 
but took me forever to identify. What occurred was when I was executing part 3 and task 2, in line for training the model I had put first 
a lowercase 'x', but a capital 'X' was supposed to be there. Then I fixed that error and ran the cell in part 3 before running task 2, 
but it showed that there was still an error. Then the suppose problem was my indentation, but after looking over and even retyping some of
the code I saw that was not the issue either. This is the part that taught me about patience and remebring there is always a solution, 
that is a given, so then I go back to part 3 and as I am looking over the code I realized that is where the problem was coming from. Even
though it had ran successfully, there was an issue in the format, which was interrupting my task 2 from running successfully. Then I
fixed the format by inputting proper indentions; I ran it, then ran task 2 right after and finally that green checkmark appeared. My 
overall takeaway from this assignment, was being able to learn about regression and the accuracy as well as the number in error in 'fare'
and why it was written in a decimal, and seeing how it is squared. I learned that in order for the codes to work, the prior code imputed 
has to be properly executed because otherwise the codes going further will not run.




---

### Member 5 — Hashim Sayed Hoosini
The primary goal of this lab was to explore the differences between regression and classification using the Titanic dataset. I used regression to predict continuous ticket prices and classification to predict distinct survival categories. This hands-on practice helped me transition from raw data preparation to building and evaluating real-world models.

In my regression task, I used a LinearRegression model to predict fares based on passenger age and class. I evaluated the model using Mean Squared Error, which resulted in an RMSE showing that my predictions were off by $58.01 on average. This proved that predicting exact financial variables remains highly complex.

Conversely, my classification task used a LogisticRegression model to predict whether a passenger survived or died. This classifier achieved a 74.83% accuracy score on test data. A correlation heatmap supported this by highlighting strong relationships between survival and both gender and passenger class.

Overall, this lab showed me that building a model is only half the work. Fixing pipeline bugs and setting up proper evaluations taught me that data preparation and data cleaning are just as critical to machine learning success as the algorithms themselves.





LLM used:
Code copilot 
Google AI mode
Purpose: writing code, spelling check,  fix grammar problems.


**Reflection:**

[Write your personal reflection here.]
