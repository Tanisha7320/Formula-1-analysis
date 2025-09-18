# Formula-1-analysis
Predictor model

Project Motivation:
I believed that driving a car was an easy task, and so I always considered Formula 1 (F1) to be a rather silly sport - anyone can drive a car right? But not an F1 car. This summer, I educated myself on the intricacies of motorsport and am now appalled by the ignorance of my former self. The sheer reflexes, neck strength and endurance required simply to drive an F1 car are beyond the grasp of most human beings. Winning an F1 race is entirely another ballgame, a game involving hundreds of engineers, intricate strategies and innovative design choices.  The aspect of F1 racing that interests me most is the pit stops, which are moments during the race when teams change the tires on the racecars (as the cars go so fast that the tires degrade extremely quickly). Pit stops matter immensely because a well-timed tire change can grant a significant advantage: if a driver changes tires before the driver ahead, they might gain track position as their car can go faster on fresh rubber. However, if a driver chooses to extend a stint on older tires, they gain a few seconds on other drivers who are losing time in the pit lane. Understanding and optimizing these strategic decisions is key to victory. 

Project goal:
This project aims to predict a driver's final race status using a machine learning model. The central question is: Can we predict whether a cars finishing status (T1-T3, T3-T10, or other) based on strategic and performance data.
- Model: Random Forest Classifier
- Target Variable: finishing_status (e.g., Finished, Accident, Engine Failure)

Key Features:
- starting_grid_position
- number_of_pit_stops
- average_pit_stop_duration
- constructor (Team)
- circuit

Current status & next steps:
The baseline model has been built and validated. Current efforts are focused on improving its predictive power through feature engineering. 
In Progress: Integrating weather data (e.g., rainy_race) to account for its significant impact on race outcomes.
Next Steps: Incorporate tire data, such as the compounds used (soft, medium, hard) and the length of each stint, to add another layer of strategic information to the model.
