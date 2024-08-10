 > # Email Campaign Effectiveness Prediction
 > **AlmaBetter Verified Project** - [**Credentials**](https://certificates.almabetter.com/en/verify/20469768274537)

 > Click on the following link to check out the video presentation and the colab file.
- [Colab]()
- [Video](https://drive.google.com/file/d/1B7HrFcQbgcZ2xx5PGmhqKyC8f6xvcbhk/view?usp=sharing) 

 > ## Project Summary :-
 > This project aims to create a machine-learning model to characterize and track emails sent through Gmail-based email marketing campaigns. This model will be used by
  small to medium-sized business owners who are looking to improve the effectiveness of their email marketing efforts and increase customer retention.
 > One of the main challenges in email marketing is determining which emails are being read, ignored, or acknowledged by the reader.
  Business owners can tailor their marketing efforts and increase their chances of success by understanding which emails are most effective at engaging the reader.

> ## Problem Statement :-
 Most of the small to medium business owners are making effective use of Gmail-based Email Marketing Strategies for offline targeting of converting their prospective customers
 into leads so that they stay with them in Business. 

 > ## Conclusion :-
 > ### Exploratory Data Analysis:

> * ### In the customer location feature we can find that irrespective of the location, the percentage ratio of emails being ignored, read, and acknowledged are kind of similar.
> * ### It does not exclusively influence our target variable. It would be better to not consider location as a factor in people ignoring, reading, or acknowledging our emails.
> * ### We observed that Email_Campaign_Type was the most important feature.
> * ### If your Email_Campaign_Type was 1, there is a 90% likelihood of your Email being read/acknowledged.
> * ### It was observed that both Time_Email_Sent and Customer_Location were insignificant in determining the Email_status. 
> * ### The ratio of the Email_Status was the same irrespective of the demographic or the time frame the emails were sent.
> * ### As the word_count increases beyond the 600 mark we see that there is a high possibility of that email being ignored.
> * ### The ideal mark is 400-600. No one is interested in reading long emails!For modeling, it was observed that for imbalance handling Oversampling i.e. SMOTE worked way better than
> * ###   undersampling as the latter resulted in a lot of loss of information.
> * ### Analyzing total past communications, we can see that the more the number of previous emails, the more it leads to read and acknowledged emails. This is just about making a connection with your customers.

> ## Modeling:-
> * ###  Imbalanced Class Handling techniques such as Undersampling and SMOTE were done after the train-test split only on the training data, to make sure that the model doesn't catch up to the test 
> * ###  set at all and it remains unknown which somewhat reduced our results.
> * ###  It is observed that SMOTE worked considerably better than Random Undersampling, it may have led to loss of information.
> * ###  The Decision Tree Model is overfitting. It is working great on train data and worse on test data.
> * ###  Hyperparameter tuning isn't improving the results to a great degree.
> * ###  The XGBoost Algorithm worked in the best way possible with such imbalanced data with outliers.
