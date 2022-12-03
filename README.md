# Insurance-Claim-Prediction.  Dataverse Hack
This is a repository to Dataverse Hack 2022 from [Analytics Vidhya](https://datahack.analyticsvidhya.com/contest/dataverse/?utm_source=sendinblue&utm_medium=email&utm_campaign=04-Nov-2022||&utm_content=registrations#About/)


<img width="1168" alt="rating_analitycsvidhya" src="https://user-images.githubusercontent.com/8630013/205440154-e016797d-e793-459a-9cdf-cc31f277855f.png">


About Hackathon:
Insurance Claim Prediction

An insurance policy is an agreement between a company and a customer by which a company undertakes to provide a guarantee of compensation for specified loss, damage or illness in return for the payment of a specified premium. A premium is a sum of money that the customer needs to pay regularly to an insurance company for this guarantee.

For example, you pay a premium of Rs. 3000/- each year for car insurance with a coverage of Rs. 100,000/-. Unfortunately, in case of an accident, the car is severely damaged. In that case, the insurance provider company will bear the cost of damage etc. for up to Rs. 100,000. 

Now if you are wondering how can a company bear such a high cost when it charges a premium of only Rs. 3000/- per year only i.e. where the concept of probability comes into the picture. For example, there might be thousands of customers who would be paying a premium of Rs. 3000 every year just like you, but only a few of them (say 2-3) would have had an accident that year and not everyone. This way everyone shares the risk of everyone else.

Our client is an Insurance company that provides insurance for cars to its customers. In this hackathon, you will be closely working with the insurer in understanding the behaviour of the policyholders.

Insurance Claim Prediction

Predict whether the policyholder will file a claim in the next 6 months or not.

Steps of my solution:
1. Univariate analisys of features. Check for normal distribution and outliers
2. Bivariate analisys of features. Check for correlation between features and target variables
3. Check for Correlation matrix
4. Feature Engineering. Created new features 'max_torque_scalar' and 'max_power_scalar'
4. Dummy work with 'transmission_type' and 'rear_brakes_type'
6. Mapping features 'is_esc','is_adjustable_steering','is_tpms','is_parking_sensors','is_parking_camera',
            'is_front_fog_lights','is_rear_window_wiper','is_rear_window_washer','is_rear_window_defogger',
           'is_brake_assist','is_power_door_locks','is_central_locking','is_power_steering','is_driver_seat_height_adjustable',
           'is_day_night_rear_view_mirror','is_ecw','is_speed_alert'
 7. One hot encoding for 'area_cluster', 'make', 'segment', 'model', 'fuel_type', 'engine_type', 'steering_type'
 8. The dataset is imbalanced
7. Modelling. Models: Desicion Tree Classifier, Random Forest Classifier, AdaBoost Classifier.
My final model is Random Forest Classifier f1_score=0.122254758418741 for train and f1_score=0.117362955807776 for test





