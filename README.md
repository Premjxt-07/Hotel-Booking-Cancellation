# Hotel-Booking-Cancellation
It's a machine learning project based on booking cancellation norm. It will try to predict whether the booking will be cancelled or not.

About the Project
It's a machine learning classification project that will try to predict whether a booking will be cancelled or a booking will not be cancelled using machine learning based on historical data.

Problem Statement
With the increase trend of cancellation from year to year, some hotel have think that high cancellation in hotel is the new norm of the industry which is a completely wrong approach, one out of four hotel guests are cancelling hotel booking ahead of a stay. This cancellation trend has effect the hotel not being able to accurately forecast occupancy within their revenue management, and the trend of cancellation also have causes hotel loss in opportunity cost (unsold room due to cancellation)

Goals
1. The Goals of this project is to find out the characteristic of customers who cancelled and finding a pattern in cancelled booking by doing an exploratory data analysis
2. Building classification machine learning model to predict cancellation, that has accuracy score around 0.75 - 0.9
3. Build and Deploy web application / dashboard using flask from our machine learning algorithm, that can predict of cancellation based on user input

Business Questions
List of Questions to help project goals
1. How Market Segment Of Booking Affecting Cancellation ?
2. How’s a lead time of a booking affecting cancellation ?
3. How’s different deposit type affecting cancellation of a booking ?
4. How does cancellation rate of booking from India and booking that’s made outside India ?
5. What Are The Other Factors that affecting cancellation of booking ?
6. What machine learning algorithm that has the highest accuracy when it comes predicting hotel booking cancellations ?

Workflow

Data Cleaning :
 Imputing missing value with median / mode (based on the context) using median instead of mean here because there are many outliers in the dataset
 Dropping columns that has more than 30% missing values
 Dropping rows with abnormal values
 0 Total guests / adults in the booking
 negative daily rate
 Dropping row with outliers that's super different compared to the other row in the columns
 Row with daily rate that's above 5000 INR
 
Exploratory Data Analysis :
 Feature Engineering
 Binning
 Aggregating Columns
 Visualization
 Insight & Conclusion

Feature Selection for machine learning process
 Label encoding for certain columns that needs to be encoded
 Association checking using dython
 Feature selection based on EDA and dython association

Model Building:
 Train Test Split
 Using pipeline for model building
 scaling for numerical features
 label encoder for categorical features
 Creating base model with few algorithm (Logistic Regression, K Neighbors Classifier, Decision Tree Classifier, Random Forest classifier, XGB Classifier)
 Checking evaluation matrix
 Hyperparameter tuning on all algorithm
 checking evaluation matrix on the tuned model
 Export the model with the best accuracy score
 
 Dashboard Building Using Flask
 



