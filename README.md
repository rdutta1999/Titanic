# Titanic
 Predicting the Survival Chances for Titanic Passengers

 The **Dataset** can be downloaded from [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/3136/download-all) on Kaggle. The **Train** and **Test** csv files are then placed in the **same directory** where the IPYNB file resides.
 
 After loading the Data, we perform **Feature Preprocessing** by **removing Outliers** and **replacing missing values** with the **median/mode** of the corresponding Features. We also combine and create a number of **new Features**. We then **drop** all the **unncessary Features**. 
 
 We try out a number of Classification Models namely **Random Forest, Gradient Boosting and XGBoost Classifiers**. Out of these three, we see that the Random Forest Classifier performs the best. So, we use it to predict the Test Cases which got us a score **0.78468** when submitted to Kaggle.
