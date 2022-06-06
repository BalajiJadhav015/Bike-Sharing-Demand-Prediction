# Bike-Sharing-Demand-Prediction
ML Regression Capstone project 2
# Problem Defination
• In given dataset Rented Bike Count is dependent variable and all other are independent variable. Following to the problem we will try to put a machine learning regression model on the given dataset. Finally, with various models we are going to analyse the results.
# Problem Description
• Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
# Data Description
• The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.
# Attribute Information:

• Date : year-month-day

• Rented Bike count - Count of bikes rented at each hour

• Hour - Hour of the day

• Temperature-Temperature in Celsius

• Humidity - %

• Windspeed - m/s

• Visibility - 10m

• Dew point temperature - Celsius

• Solar radiation - MJ/m2

• Rainfall - mm

• Snowfall - cm

• Seasons - Winter, Spring, Summer, Autumn

• Holiday - Holiday/No holiday

• Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

# Hypothesis
• With EDA we can justify our hypothesis.
• In season summer bike demand will be more.(Fail to reject)
• If there is less visibility bike demand will be less.(Reject)
• In the hours 9 am and 7 pm demands will be more.(Reject)
• On Sunday bike demands will be less.(Fail to reject)
• With rainfall and snow fall demands of bike will be reduced.(Fail to reject)
# Feature Engineering 
Date from date column and Hours taken seperately with the help of Heat map we reduced highly co-related features, with VIF we finalise our features and performed various models.
# Model Implementation 
Various types of linear model are implemented on data such as Linear regression, Ridge regression, Lasso regression, Elastic net regression and Polynomial feature regression, with these models results were good but not satisfying So we have to move towards some complex models such as Decision tree regressor, Random forest regressor, XG boost regressor and Cat boost regressor.
Best results on model is obtained from Random forest regressor and XG boost regressor. After implementation of Grid search CV on both models final accuracy (r2) for XGB was more. Random forest regressor R2 train and test 0.98,0.91, XG boost R2 train and test 0.97,0.97 respectively
# Conclusion

• Bicycle sharing systems can be the new boom in India, with use of various prediction models the ease of operations will be increased. 

• During implementation of linear models accuracy obtained was not more so we moved towards more complex models.

• With application of Decision tree regressor, Random forest regressor, XG boost regressor and Cat boost regressor we got higher accuracy.

• Out of which Random forest regressor, XG boost regressor have more accuracy.

• With the application of Grid search CV on both finally we got more accuracy for XG boost regressor. As r2 = 0.97 and RMSE = 190.27.

# References 
[1] “Short-Term Prediction of Bike-Sharing Demand Using Multi-Source Data: A Spatial-Temporal Graph Attentional LSTM Approach” by Xinwei Ma 1 , Yurui Yin 1 , Yuchuan Jin 2 , Mingjia He 3 and Minqing Zhu 4

[2]https://www.computerscijournal.org/vol10no1/prediction-of-bike-sharing-demand/

[3]https://link.springer.com/chapter/10.1007/978-3-030-94751-4_25

[4] Foell, S., Phithakkitnukoon, S., Kortuem, G., Veloso, M., Bento, C., 2015. Predictability of public transport usage: A study of bus rides in lisbon, portugal. IEEE Transactions on Intelligent Transportation Systems 16, 2955–2960.

[5] Gers, F.A., Schmidhuber, J., Cummins, F., 1999. Learning to forget: Continual prediction with lstm .


Any suggestions are welcomed...







