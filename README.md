# AndroidDevChallenge

Smart Food Logger
-----------------------

How many times have you faced the challenge of using a external tool like food weighing scale while logging your calories for the day? What if, you could directly log your food intake by just the usage of your phone camera.

In the current fitness world, there are numerous apps, helping the user maintain a daily food journal. Some ask the user to do the entry manually while there are few which detect the object for the user but still depend on an external manual input to get the weight of the food item. How can we try and eliminate this external weighing scale, so that the user can log the food item from anywhere automatically. 

The Smart Foodlogger App is designed to solve this problem.

The app user can simply point the camera opened in the app to the food item,lets say an apple.
The app would recognise the object(apple), fetch relevant parameters of that object and based on a ML based algorithm will calculate the weight of the object.

Using this weight, the app can show the calorie and macronutrient distribution and advice the user whether eating that food item would be beneficial or not. The train data(of food densities and volumes) along with the users validated(validated by the user from the app) train data will help our apps ML model to predict any weights further along.
