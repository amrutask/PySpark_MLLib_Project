# Machine learning on Databricks using Spark ML library
**Machine Learning using PySpark**
********************************************************************************************************************************
## Linear Regression Consulting Project**

### Problem Statement:**

You've been contracted by Hyundai Heavy Industries to help them build a predictive model for some ships. 
Hyundai Heavy Industries is one of the world's largest ship manufacturing companies and builds cruise liners.

You've been flown to their headquarters in Ulsan, South Korea to help them give accurate estimates of how many crew members a ship will require.

They are currently building new ships for some customers and want you to create a model and use it to predict how many crew members the ships will need.

Here is what the data looks like so far:

Description: Measurements of ship size, capacity, crew, and age for 158 cruise
ships.


Variables/Columns: 
* Ship Name     1-20
* Cruise Line   21-40
* Age (as of 2013)   46-48
* Tonnage (1000s of tons)   50-56
* passengers (100s)   58-64
* Length (100s of feet)  66-72
* Cabins  (100s)   74-80
* Passenger Density   82-88
* Crew  (100s)   90-96

It is saved in a csv file for you called "cruise_ship_info.csv". Your job is to create a regression model that will help predict how many crew members will be needed for future ships. 
The client also mentioned that they have found that particular cruise lines will differ in acceptable crew counts, so it is most likely an important feature to include in your analysis!

****************************************************************************************************************************************
**Logistic Regression Consulting Project**

**Problem Statement:**
We have a titanic dataset with the passengers information such as age, gender, passenger's class, fare, etc. We need to identify which passenger survive titanic crash based on their personal information.

Columns:
'PassengerId',
 'Survived',
 'Pclass',
 'Name',
 'Sex',
 'Age',
 'SibSp',
 'Parch',
 'Ticket',
 'Fare',
 'Cabin',
 'Embarked'
 
 The columns also contain some null values. There are some categorical columns.
 Use binary classification to classify if a passenger survived as 1 and not survived as 0.
 
 ***************************************************************************************************************************************
 
 **Tree Methods Consulting Project**
 
 **Problem Statement:**
 
You've been hired by a dog food company to try to predict why some batches of their dog food are spoiling much quicker than intended! Unfortunately this Dog Food company hasn't upgraded to the latest machinery, meaning that the amounts of the five preservative chemicals they are using can vary a lot, but which is the chemical that has the strongest effect? The dog food company first mixes up a batch of preservative that contains 4 different preservative chemicals (A,B,C,D) and then is completed with a "filler" chemical. The food scientists beelive one of the A,B,C, or D preservatives is causing the problem, but need your help to figure out which one! Use Machine Learning with RF to find out which parameter had the most predicitive power, thus finding out which chemical causes the early spoiling! So create a model and then find out how you can decide which chemical is the problem!

Pres_A : Percentage of preservative A in the mix
Pres_B : Percentage of preservative B in the mix
Pres_C : Percentage of preservative C in the mix
Pres_D : Percentage of preservative D in the mix
Spoiled: Label indicating whether or not the dog food batch was spoiled.
