# Fitness-Dataset-analysis
A machine learning project to analyze the Relationship between attendance and number of months as a member


GoalZone, a fitness club chain in Canada, is facing a challenge where some of their fitness classes are always fully booked but have low attendance rates. To increase the number of available spaces for classes, GoalZone wants to predict whether a member will attend a class or not, so they can make another space available if a member is predicted to not attend.

The dataset used for this project contains records of each time a member registered for a fitness class. It includes columns such as booking_id, months_as_member, weight, days_before, day_of_week, time, category, and attended. The data was preprocessed by replacing missing values and ensuring the values matched the given descriptions in the table. There were no missing values in the attended column, which is the target variable.

A visualization was created to show how many bookings attended the class, which revealed that the category with the most observations for attended is 1 (attended). The observations were not balanced across categories, as the number of attendees was significantly higher than non-attendees.

This is a classification machine learning problem, where the goal is to predict whether a member will attend a fitness class or not.
