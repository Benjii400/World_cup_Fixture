# World cup fixtures

# The objective of the project.

This project was made to make fixtures of world cup in 4 groups with 4 teams in each group randomly and after that make a graph analysis for the teams in the group. 

# ****Audience**** of the project.

This project is meant for peoples who are interested in making random fixtures of football and likes making analysis.

# ****Data Collection****

Data of this page are collected from world country list api  country flag api height chart and the user.

# ****Structure**** of the project.

We first have a button that says fix and 4 cards with empty un order lists. when we click the button fix the data will be fetched and list of for will be created for each card (List of four is created using for loop) the list contains the name of a country picked randomly using Math.random() and also contains the corresponding flags of the country lastly it contains an input for the points and a button called generate to generate the graph. Then the list is appended to unordered list.

When the button generate is clicked we create four variables for the four teams in a group and store the values of the user entered in the inputs.(The inputs have validation.)

Finally we get two charts from high charts and change their values with the variables above.