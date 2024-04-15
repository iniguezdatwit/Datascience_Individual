# Datascience_Individual

# Introduction 
I will be analyzing a dataset that contains information on metrics of different models of EVs including speed, efficency, range, and price. The aim of this project is to use this dataset to answer questions that would benefit a potential buyer these questions are as follows. 1. what vehicles have the best range with great efficiency as even if a viecle has a high range it might have poor efficency. 2.what vehicles have the top speed for each of the drive types as buyers may perfer a specific drive type. 3. what vehicles have the fastest charge speed and which have the slowest as buyers may be concerned wil low charge speed.

# Selection of Data 
Analysis and Vizualization were done on google collab 
Using this dataset Electric Vehicles Dataset: https://www.kaggle.com/datasets/kkhandekar/quickest-electric-cars-ev-database, the original file contained 180 entries with 11 column categories. Data cleaning was necessary as some data entries had empty fields so those entries were removed. data columns used in this project were name, top speed, range, charge speed, efficency and drive.

# Methods
google collab was used to code, and main methods for data analysis were Pandas and Numpy and for vizualization Matplotlib.
# Q1:
the data of Range and efficiency are normalized to make it easier to find the car that has good range as well as efficiency and a scatter plot was made to vizualize the cars with range and efficiency on the axises 
# Q2:
for loops are used to shift through a sorted index version of topspeed then grabbing the first index that matches one of the drive types thus getting the top speed for that drive type. a scatter plot was used to show the speeds for all three drive types.
# Q3:
standard numpy fuctions were used to obtain the min max and average charge speeds as well as using the index of min and max to get the name of the cars who those belongs to. as there are a lot of cars a top ten and a bottom ten charging speed bar graphs were used for vizualization.

# Results
# Q1:
EV with the best range and efficiency red point:   Tesla Roadster 
image of chart in graph folder
# Q2:
car with top speed in all wheel drive is  Tesla Roadster 
car with top speed in rear wheel drive is  Porsche Taycan 
car with top speed in front wheel drive is  Renault Megane E-Tech Electric
image of chart in graph folder 
# Q3:
Max Charge Speed: 1410 km/h belonging to:  Lucid Air Pure
Min Charge Speed: 150 km/h belonging to:  Lexus UX 300e
Average Charge Speed: 530.0 km/h
image of charts in graph folder

# Discussion 
for question one it seems if you are a consumer that roadtrips often or a person who doesnt want to charge often the tesla roadster would be a good ev choice. Question 2 if you are a consumer so likes to take tops speed into account with prefrences for drive type for varing applications the tesla roadster for all wheel, Taycan for rear and megane e tech for front. and finally for question 3 if you care about how long you spend charging your car so you can get back on the road the lucid air seems the choice having the fastest charge. with the lexus if youre a more patient person. for future analysis US cost of these cars could be crossed with these previous questions to see what car is more bang for buck for the us consumer.

# Summary
This alaysis provides consumers a helpful hand in choosing an ev based on common categories used when buying cars with the Tesla Roadster being the best for question 1 and 2  despite without having the faster charge speed meaning that the lucid could have very poor efficency and loose charge faster.

# refrences 
https://www.kaggle.com/datasets/kkhandekar/quickest-electric-cars-ev-database
