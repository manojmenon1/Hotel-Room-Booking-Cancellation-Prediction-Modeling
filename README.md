# Hotel-Room-Booking-Cancellation-Prediction-Modeling
This project explores the use of Machine Learning Techniques to identify key factors influencing a high number of cancellations of Hotel Room Bookings and to build a Machine Learning model that can predict which booking is going to be canceled, in advance and help in formulating profitable policies for cancellations and refunds.

## Data Description
The data contains the different attributes of customers' booking details. The detailed data dictionary is given below.

## Data Dictionary
Booking_ID: the unique identifier of each booking
no_of_adults: Number of adults
no_of_children: Number of Children
no_of_weekend_nights: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
no_of_week_nights: Number of weeknights (Monday to Friday) the guest stayed or booked to stay at the hotel
type_of_meal_plan: Type of meal plan booked by the customer:
Not Selected – No meal plan selected
Meal Plan 1 – Breakfast
Meal Plan 2 – Half board (breakfast and one other meal)
Meal Plan 3 – Full board (breakfast, lunch, and dinner)
required_car_parking_space: Does the customer require a car parking space? (0 - No, 1- Yes)
room_type_reserved: Type of room reserved by the customer. The values are ciphered (encoded) by INN Hotels Group
lead_time: Number of days between the date of booking and the arrival date
arrival_year: Year of arrival date
arrival_month: Month of arrival date
arrival_date: Date of the month
market_segment_type: Market segment designation.
repeated_guest: Is the customer a repeated guest? (0 - No, 1- Yes)
no_of_previous_cancellations: Number of previous bookings that were canceled by the customer prior to the current booking
no_of_previous_bookings_not_canceled: Number of previous bookings not canceled by the customer prior to the current booking
avg_price_per_room: Average price per day of the reservation; prices of the rooms are dynamic. (in euros)
no_of_special_requests: Total number of special requests made by the customer (e.g. high floor, view from the room, etc)
booking_status: Flag indicating if the booking was canceled or not.

## Methodology

### Define the problem and perform an Exploratory Data Analysis
- Problem definition
- Univariate analysis
- Bivariate analysis
- Use appropriate visualizations to identify the patterns and insights
- Key meaningful observations on individual variables and the relationship between variables

### Data Pre-processing
Prepare the data for modelling:
- Missing value Treatment (if needed)
- Outlier Detection(treat, if needed)
- Feature Engineering (if needed)
- Data split

### Model building - Logistic Regression
- Build the Logistic Regression model using statsmodels library and comment on the model statistics
- Check assumptions of Logistic Regression
- Provide interpretations based on coefficients obtained from the logistic regression model
- Comment on model performance

### Model Performance evaluation and improvement - Logistic Regression
- Try and improve the model performance by changing the classification threshold
- Comment on model performance after changing the threshold

### Model building - Decision Tree
- Build the model and comment on the model performance.

### Model Performance evaluation and improvement - Decision Tree
- Try and improve the model performance by pruning
- Comment on model performance
- Find the decision rules and check feature importance

### Actionable Insights & Recommendations
- Compare decision tree and Logistic regression models
- Conclude with the key takeaways for the business
