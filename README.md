# Group-Assignment-Demographic-Prediction-based-on-website-keywords

Mélodie Chang
Daniel Barrios 
Pei-Hsiu SHIH
Olympia Hilverda


For this assignment we were asked to predict gender and age for a group a internet visitors, based on their online behaviour: the keywords they searched for. 

For cleaning data, first, the column ID is not unique. We wanted to predict gender and age for each unique person so we decided to aggregate the keywords based on ID. 

Then, we tried the gender prediction with different cleaning methods:
- Text cleaning 
- Removing the frequencies since most words only appeared once
- Removing stop words
- Stemming to reduce dimensionality 

We tries Naive Bayes, Decision Tree, Random Forest and Gradient Boosted Trees. Our best model ended with a test accuracy of 0.66, using Naive Bayes

For age, we separated to different ages into 10 different age groups (people in their 30s, 40s etc.) to increase accuracy. Our best model was with the MLPC Classifier. 
