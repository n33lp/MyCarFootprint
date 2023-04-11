MyCarFootprint

Assignment 1 for CMPUT301 Winter 2023 at uAlberta


Problem Description
Consider the situation of someone who wants to track their driving-related carbon footprint. Make a simple, attractive, intuitive Android mobile app to help users track their gas consumption and calculate their carbon footprint. Let us call this app: MyCarFootprint.

Using this app, users can keep track of their visits to gas stations. Specifically, each gas station visit has the following editable fields:

Gas station name (textual, up to 30 characters)
Date (presented in yyyy-mm-dd format)
Fuel type (Gasoline or Diesel)
Amount in litres (positive integer)
Price per litre in dollars (positive, two decimal places)
Additionally, each gas station visit has the following calculated fields (can not be edited):

Fuel cost in dollars (rounded to two decimal places)
Carbon footprint (carbon dioxide emission) in kg CO2, rounded to the nearest integer (see the coefficients below)
The app must allow the user to:

Show a list of gas station visits
Add a new gas station visit (which always appends to the bottom end of the list)
View and edit the details of an existing gas station visit, including the gas station name, date, fuel type, amount and price
Delete a gas station visit
See the total fuel cost and the total carbon footprint below the list
The list need not show all the information for an item if screen space is limited. Minimally, each item in the list should show its name, fuel type, and carbon footprint.

Coefficients to calculate the carbon footprint (carbon dioxide emissions)

Gasoline: 2.32 kg CO2 per 1 litre
Diesel: 2.69 kg CO2 per 1 litre
(source: https://www.eia.gov/environment/emissions/co2_vol_mass.php)

Marks gotten 8/8

The app must assist the user in proper data entry. For example, use appropriate user interface controls to enforce particular data types and avoid illegal values.

For this assignment, the data need not be persistent across runs of the app.

Encode your campus computing ID in the app name. Specifically, the app name must show up as YOURCCID-MyCarFootprint (e.g., kennyw-MyCarFootprint).


