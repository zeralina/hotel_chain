# hotel_chain
The clients of the hotel chain have an opportunity to cancel their reservations, which leads to the fact that some rooms are empty even in high season. The company management would like to introduce the practice of overbooking - the possibility of booking more rooms than the hotel has available.
But an ill-conceived system of overbooking can lead to the fact that guests will really have nowhere to stay. Therefore, my task is to make a high-quality and accurate forecast of overbooking failures.

 __Steps:__
- Perform basic data preprocessing: fill in gaps, clean duplicate data, perform scaling.
- Perform advanced data preprocessing: construct new features (feature engineering) and remove all unnecessary ones.
- Immerse yourself in the specifics of the data being processed: calculate basic descriptive statistics and build several visualizations.
- Build a logistic regression model, which will take as input the data known to the hotel before check-in, and give a forecast as output: whether the client will cancel the booking or not. Evaluate the accuracy of the obtained forecast.
