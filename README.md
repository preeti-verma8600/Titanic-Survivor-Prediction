# preeti-verma8600 Titanic-Survivor-Prediction
RMS TITANIC was a British  passenger liner that started its journey with 2200   passengers and four days later sank in the Northern Atlantic Ocean in the early morning of 15th April 1912. Around 1500 people died and 700 survived the tragedy.     In this project, a model is build that could successfully determine chance of survival and derive conclusions using different models .
Problem description-
         Need to predict the probability of survival  based on the data available( train.csv).
         Also, to confirm the claims made by certain other sources that survivors belonged to one of the following categories: women, children & / or upper class.
Library Used
              1- For Analyzing: Numpy, Pandas
              2- For Visualization: Matplotlib, Seaborn 
Models used -(1) Logistic Regression 
             (2) Random Forest 
             (3) KNeighborsClassifier
             (4) Naïve Bayes
Conclusion -
Comparing the accuracy of the different models, Random Forest is the best model followed by KNN.
Random Forest highlights the importance of predictors Sex, Pclass, Age, Fare.
 After analyzing all the models we can conclude that predictors Sex, Pclass and Age did played a major role for Titanic survivors.
 Women, children, and first class passengers as well as people with a small family had a better chance at survival.
 The Embarked doesn’t seem to have an effect as the percentages are in line with the amount of people embarked from each port. 
