# Summer_analytics
# Overview
This project implements a dynamic pricing system for parking lots using real-time occupancy data.  
It simulates a streaming environment, applies logistic pricing logic, and visualizes the output using Bokeh and Panel.  
The goal is to explore demand-based pricing strategies for smarter urban parking.
For model 1(Capstone1_stripped), we have predicted price using a logistic function. Features taken into were the occupancy and capacity and the bokeh plot was developed keeping the datetime on the x axis and the predicted price on the y axis.
For model 2(capstone2), we have predicted price from the normalized demand value using a linear function with the inputs as the occupancy, capacity, isspecialday, traffic nearby, queue length and vehicel weight. encoding is also done for the traffic nearby and vehicle weight as it contained categorical data.
For model 3(capstone3), we have suggested rerouting of the vehicles based on the distance with the nearby plot if a particular parking lot is full. Distances are calculated using Haversine formula and distances are calculated using those coordinates of the parking lot.

# Tech stacks
python,
Numpy,
Pandas,
Pathway,
Bokeh plot,
Panel.

this image below contains full architecture of what all models i have made and what all features from the given dataset were used in that model.
![Untitled diagram _ Mermaid Chart-2025-07-09-180405](https://github.com/user-attachments/assets/6be28a7f-8bde-432e-89e2-186b39fce349)


