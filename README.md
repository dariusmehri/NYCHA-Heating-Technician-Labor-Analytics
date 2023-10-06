### NYCHA Heating Technician Labor Analytics

#### Background and Objectives
The objective of this project is to identify Heating Plant Technicians (HPTs) who are not in compliance with the rules and laws stipulated in the HUD Agreement and Housing Code that requires temperature readings to be properly recorded. When a resident complains about loss of heat in their unit an HPT is sent to determine if there is an issue at the site. The HPTs are required to take a temperature reading and submit a picture of the reading.  Many HPTs frequently record the same temperature combination (70 degrees for the apartment and 120 for the hot water) indicating they are engaged in deceptive practices. The objective of this project is to identify actors who are willfully deceiving the agency.

#### Process and Approach
1. An algorithm in Python was created to generate a list of bad actors who frequently recorded the 70-120 apartment/hot water combination.
2. Visualizations in Tableau are used to explore patterns of bad behavior.

#### Results
##### Time Series Analysis
Repeated reporting of the 70-120 temperature combination over time indicates deceptive practice. The 70-12 temperature combination is colored in orange, the other combinations are shaded out.

![Time Series](https://github.com/dariusmehri/NYCHA-Heating-Technician-Labor-Analytics/assets/11237613/ee319b75-26ed-454f-8026-c385c7da2716)


##### Temperature Mode
Analysing the most frequently recorded temperature is an effective way of identifying deceptive practice. The highlighted column shows the mode relative frequency, the rate at which the HPTs record a 70-120 combination. The employee at the top of the table records a 70-120 combination 97% of the time. 

![Temp Mode](https://github.com/dariusmehri/NYCHA-Heating-Technician-Labor-Analytics/assets/11237613/8fc8f893-4514-4db7-af88-2caa6955c870)

The frequency of the temperature combination can also be visualized using a rotated bar chart.

![Temp Combos](https://github.com/dariusmehri/NYCHA-Heating-Technician-Labor-Analytics/assets/11237613/b2c8c0f1-7c4d-4295-bc54-0936b3c7e6e4)

##### Spatial Analytics
The map shows where the 70-120 combination is occuring most freqently. The spatial points are sized by the number of 70-120 combinations reported to the agency.

![map](https://github.com/dariusmehri/NYCHA-Heating-Technician-Labor-Analytics/assets/11237613/3e6ede65-e44f-44e7-971c-9d0d64e25d65)



