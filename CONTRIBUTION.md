# Lab 06 — Regression and Classification
## Group 4 — Individual Contributions

**Course:** ITAI 1371 — Introduction to Machine Learning  
**Lab:** Module 06 — Regression and Classification Models

---

### Member 1 — Patrick Rostand Gandjouon Tchassem

**My Contribution:**

For this lab, I worked on completing and testing the Linear Regression and Logistic Regression exercises in Google Colab. I trained the Linear Regression model to predict Titanic passenger fares using Age and Pclass. I also ran the model evaluation and checked the Mean Squared Error result of 3364.92.

I worked on the Logistic Regression exercise by training the model to predict passenger survival using Age, Pclass, and Sex. I ran the predictions and verified the accuracy result of 74.83%. I also completed the three knowledge-check questions by explaining the differences between regression and classification, interpreting the model coefficients, and describing why different evaluation metrics are used.

After completing the exercises, I reviewed the notebook outputs and exported the completed notebook as a PDF. I also created the shared reflection and contribution Markdown files so each group member could add their own work and learning experience.

---

### Member 2 — Kenneth Kouokam

My contribution to the Module 06 lab focuses on reviewing and explaining the data preparation and
train/test splits used before model training. This includes how the Titanic dataset is loaded into
pandas and why rows with missing Age values are removed in this notebook. My section identifies
Age and Pclass as the input features for predicting Fare. For survival prediction, it explains the use of
Age, Pclass, and Sex as inputs, with Survived as the target. It also covers the encoding of Sex, where
male is represented by 0 and female by 1.

My part also explains how both prediction tasks use an 80/20 train/test split with random_state=42.
The training portion allows each model to learn relationships, while the test portion provides separate
examples for evaluating its predictions. Keeping the split reproducible helps the group compare
results using the same starting conditions. This review supports the group by documenting how the
inputs and targets are prepared and why the evaluation data must remain separate from training. My
focus is the preparation and explanation of the workflow leading into the two models

---

### Member 3 — Saimi Manasiya

My contribution to this lab was focused on Task 3, which involved model interpretation and answering the knowledge-check questions. I worked on understanding and explaining the differences between regression and classification and how each method is used for different prediction tasks. I also focused on interpreting the coefficients of the Linear Regression model by printing lr_model.coef_ and understanding their relationship to the Age and Pclass features in the specified order. In addition, I explained why MSE is used to measure errors in fare prediction and why accuracy is used to evaluate survival classification. While working on this task, I reviewed the model outputs and connected the results to the concepts learned in class. This helped me develop my analytical and problem-solving skills and improve my ability to explain machine learning results in simple terms. Through this contribution, I gained a better understanding of how to evaluate and interpret models and how these concepts can be applied when working with real-world datasets such as the Titanic dataset.






### Member 4 — Anavictoria Cavazos

My Contribution:

My personal contribution for assignment 06 was to communicate within my group about the completion of the assignment, as well as 
providing help amongst us when needed. Aside from the usual communication with my group I made sure to complete the Google Colab 
independently to understand the concept or topic being shown in 06. When doing 06 I made sure to compare what I ended up with and to the 
colab selected to turn in.
In doing so it helps to make sure it was done properly and to assure that I also properly completed it, that way 
mistakes are avoided or noticed before considering it as successfully completed.

---

### Member 5 — Hashim Sayed Hoosini

**My Contribution:**

My contribution to this lab focused on running the experiments independently. By completing this lab, I learned that regression is used to predict a continuous numerical value—such as predicting that a passenger's ticket price.
Conversely, I learned that classification is applied when predicting a discrete label or category, such as determining whether a passenger falls into the "survived" or "died" category.
Furthermore, I gained a deeper understanding of why we evaluate regression models using mean squared error (MSE), while relying on accuracy score for classification models. Each of these steps significantly enhanced my overall understanding of both regression and classification methodologies.

