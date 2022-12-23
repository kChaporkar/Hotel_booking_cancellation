# Hotel_booking_cancellation

This project is about building a prediction model for hotel bookings cancellation using various classifiers such as logistic regression, decision tree, random forest, XGBoost and Neural network while using regularization, cross validation and grid search for getting best results.

<br><br>
<img src = 'https://www.gannett-cdn.com/presto/2019/05/02/USAT/5b1d7ecc-ce8d-43db-92b9-d7b61c198063-GettyImages-912299740.jpg?width=1320&height=880&fit=crop&format=pjpg&auto=webp'
     height = "600"
     width = "700"/>

<br><br>
<b>I. High Level Outline</b>

Here we are dealing with hotel booking cancellations for a large international hotel chain, and need to build a prediction model that shall help us predict such cancellations in order to take preventive measures to save on revenue loss.

<b> While we are using the available data to predict future cancellations, there are certain qualitative and situation-based reasons behind cancellations which are not easy to predict. It is important to note that the model cannot consider or accomodate for such aspects which lead to cancellation of hotel bookings.</b>

At present, we are looking at the following parameters which are important for our prediction:
- Lead time (how much in advance the booking has been made)
- Arrival date
- Days of stay (weekdays and weekends)
- Travellers types (number of adults, children and babies)
- Meal type
- Country of origin
- Market segment
- Distribution channel
- Repeated guest or not
- Previous cancellations
- Previous bookings not cancelled
- Room type
- Booking changes
- Deposit type
- Agent
- Company
- Days in waiting
- Customer type
- Average Daily Rate
- Required car parkings
- Special requests

<b>II. Brief Background</b>

1. What is the problem?<br>
Many hotels are facing the issue of last minute booking cacellation 
<br>
<br>
2. Why is it important?<br>
This prediction model is important for the hospitality industry which has seen a decline over the past couple of years, particularly with the Covid-19 pandemic.
Hotels have limited occupancy, and they lose out on potential revenue when they decline new customers on account of being fully booked, and then they see cancellations.
<br>
<br>
3. Who are the key stakeholders?<br>
This predictor model is beneficial for hotels and travel booking agencies.
<br>

<b>III. Cost of incorrect prediction</b>

1. False Positive<br>
In this case, model is predicting that booking will be cancelled but in reality it won't be cancelled<br>
If hotel management is sensing that booking is going to be cancelled then they might find new customer and if the booking is not cancelled eventually then management will have to deal with multiple customers with same room<br>
This can be dealt with easily by keeping the new customers on waitlist instead of directly assigning a room

2. False Negative<br>
In this case, model is predicting that booking will not be cancelled but in reality booking gets cancelled<br>
Here hotel loses potential revenue as the room will be unreserved as the booking get cancelled at the last moment<br>

- False Negatives are more costly for any hotel manegement so I would consider on reducing falls negatives by using recall as performance measure
