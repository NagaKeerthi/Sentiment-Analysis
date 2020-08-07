# Sentiment-Analysis
Main objective of the project is to build an NLP Sentiment Analysis model on the NPS survey data to segregate the reviews into 4 different sentiment categories i.e., Positive, Negative, Neutral and Mixed.

#Current Work

Unnecessary columns such as index, verbatim_UUID,Mapped_category etc  except Verbatim, Sentiment Label, Id were removed.
Data pre processing such as converting into lower case, removing punctuations and special characters has been done and created a new column and named it as Cleaned Verbatim
Implemented STOPWORDS and introduced TFIDF Vectorizer for further more processing of data
Divided the data into training and testing data with dependent and independent variables.
Built a logistic regression model with 77.24% accuracy and a random forest classifier with 74% accuracy
Built a stacking classifier and observed the top 2 accuracy to be 89% 


#Next Steps

Build tableau dashboards which could display the probability distribution of reviews among the four sentiment categories
