# BreastCancerDetection_UsingML
Detecting Breast Cancer using various Regression and Classification algorithms.  

Hello there!

This Repository is a proof of my learning journey in Machine Learning, Artificial Intelligence, and Data Analysis. 
In 3 Weeks, I was able to learn Python, Numpy, Pandas, and ScikitLearn. This project is a popular test for seeing your ML/DA Skills. 

Here's what I did: 

I loaded the CSV File into my Notebook as a Dataframe. As good practice, I checked if the Dataframe is in line with the Dataset file 
I have. After verifying that my Data has correctly loaded, I scanned the file for any NaN or Values that we don't want. Fortunately, 
the file was already clean and didn't have any NaN values. 

Since this Dataset was for Breast Cancer Detection, there's two labels (Outputs) we could've gotten. You could either have Cancer, 
or you don't have cancer. In medical terms, you are either Malignant or Benign. In the included DataSet we had values that would represent Malignant with an 'M' and Benign with a 'B'.

Since we were going to use numerical models, it was important that we encoded the labels and changed the Categorical Data to Numerical Values. After doing that, I checked if there was any correlation within the columns. Moving on, I split the Dataset into features and labels. With out labels and feautures being represented by two unique dataframes, I spotted that the data in my Dataset wasn't scaled correctly. 

Therefore, I had to Normalize my Dataset. After Normalizing my DataSet, I found deeper correlation between columns. Since correlation can affect my accuracy, I dropped features that had at least 90% correlation. With cleaner and accurately scaled features, I could move on to business. 

I made a function for my models and trained 5 models. These models were: 
1 - Logistic Regression

2 - Decision Tree

3 - Random Forest Classifier 

4 - Support Vector Machine

5 - K-Nearest-Neighbour Classifier

After training the models, I was able to get a 98% Accuracy with my KNN Model! Later on I used the KNN Model and other models to predict the labels for the testset, which I loaded to their respective files. 

I hope you like my work!
