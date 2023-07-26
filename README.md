Clever_Meal_App
Members:
Members of the group:

Iranel González
Bruna Santos
CLEVER MEAL APP 🍎🫐🥗
PROBLEM
It’s not a secret for all of us here that obesity, heart disease, and diabetes are the biggest public health problems in the world. 
We have many factors that we can use to prevent and control this and one of them is nutrition improvement.

Recently people have been more concerned about eating healthier and companies have adjusted to this and have brought solutions to these demands. 
However, we realized that many people have an interest in more specific control, such as counting calories and macronutrients. 
Proof of this it’s My Fitnesspal app which has more than 200mi users in the world. We decided to do some research to better understand this market.

We found many ideas and business models that bring interesting and practical solutions to improve eating habits, such as Hello Fresh and Purple Carrot, for example. 
But none of these companies offer personalized recipe recommendations.

How can we then improve these services that we already have to reach this public that wants something more personalized? 
Our idea then is to create a model in which based on some information from the user, we can create a personalized menu, 
with the amount of calories and macronutrients according to their nutritional goal.

OBJECTIVE
Create a recommendation model able to recommend recipes food based on the calories and macronutrient goals of the user.

METHODOLOGY
DATA INFORMATION:
Source: Recipes Dataset
Number of rows: 7062
Number of features: 6

-NOTE-
When using our database, we realized that the recipes did not follow a standard in the final amount of preparation, so the recommendation can sometimes exceed 
the amount of calories. We then thought about improving our database using the USDA API - United States Department of Agriculture. 
We got the key to carry out the requests, but even following the documentation on the USDA page, we could not get the data we needed. That is why we chose to 
continue using our database, since the predictive model is working perfectly and in the future we can improve it so that the recommendation can be even better.

MACHINE LEARNING MODEL
Unsupervised model: K-MEANS

Workflow

CONLUSIONS
