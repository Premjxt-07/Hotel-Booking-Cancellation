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

1. Imputing missing value with median / mode (based on the context) using median instead of mean here because there are many outliers in the dataset
2. Dropping columns that has more than 30% missing values
3. Dropping rows with abnormal values
4. 0 Total guests / adults in the booking
5. negative daily rate
6. Dropping row with outliers that's super different compared to the other row in the columns
7. Row with daily rate that's above 5000 INR
 
Exploratory Data Analysis :

1.Feature Engineering
2.Binning
3.Aggregating Columns
4.Visualization
5.Insight & Conclusion

Feature Selection for machine learning process:

1.Label encoding for certain columns that needs to be encoded
2.Association checking using dython
3.Feature selection based on EDA and dython association

Model Building:

1.Train Test Split
2.Using pipeline for model building
3.scaling for numerical features
4.label encoder for categorical features
5.Creating base model with few algorithm (Logistic Regression, K Neighbors Classifier, Decision Tree Classifier, Random Forest classifier, XGB Classifier)
6.Checking evaluation matrix
7.Hyperparameter tuning on all algorithm
8.checking evaluation matrix on the tuned model
9.Export the model with the best accuracy score
 
Dashboard Building Using Flask
 



