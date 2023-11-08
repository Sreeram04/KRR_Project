# KRR_Project
Drug Recommendation System

UCI ML Drug Review dataset - Dataset used (From Kaggle)

# Working:
i. Used sentiment analysis on the given dataset using LGBM Classifier(ML_Model) and LSTM(DL_model).
ii. Based on the predicted values from both model, using the equation (ml_model_score+dl_model_score)*(useful_reviews/total_reviews). 
We gave a score to each medicine.
iii. Based on the score the top two medicine for each condition was taken and added to the database.
iv. Based on user requirements, drugs were given, if the condition mentionedd by user not in the database.
v. We use LLAMA 2 Large language model to give out solutions to their problems and add this to data to the database
