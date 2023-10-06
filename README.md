### NYCHA Heating Technician Labor Analytics

#### Background and Objectives
The objective of this project is to identify Heating Plant Technicians (HPTs) who are not in compliance with the rules and laws stipulated in the HUD Agreement and Housing Code that requires temperature readings to be properly recorded. When a resident complains about loss of heat in their unit an HPT is sent to determine if there is an issue at the site. The HPTs are required to take a temperature reading and submit a picture of the reading.  Many HPTs frequently record the same temperature combination (70 degrees for the apartment and 120 for the hot water) indicating they are engaged in deceptive practices. The objective of this project is to identify actors who are willfully deceiving the agency.

#### Process and Approach
1. An algorithm in Python was created to generate a list of bad actors who frequently recorded the 70-120 apartment/hot water combination.
2. Visualizations in Tableau are used to explore patterns of bad behavior.

#### Results
##### Time Series Analysis
Repeated reporting of the 70-120 temperature combination over time indicates deceptive practice. The 70-12 temperature combination is colored in orange, the other combinations are shaded out.

![Time Series](https://github.com/dariusmehri/NYCHA-Heating-Technician-Labor-Analytics/assets/11237613/98a6602f-7ca4-4c4b-bfc4-0b13cb504675)

