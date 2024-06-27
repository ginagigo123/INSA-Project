# INSA Project
The project is related to the analysis and prediction of pig's postures.

## Data Description
The dataset comprises several columns with information about pig behavior and environmental conditions. The "posture" column describes the posture of the pig, while "x" and "y" represent the coordinates of its position. "Speed" indicates the velocity of the pig's movement. "Week" denotes the week number, and "ind" serves as the individual identification number for each pig. The "traitement(treatment)" column specifies whether the pig received treatment, with values indicating the addition of sugar cane or not. "Breed" provides details about the breed of the pig. "Time" and "date" indicate the time and date of observation, respectively. "Temperature" records the temperature at the time of observation. Finally, "detail_time" offers more precise timing information, and "weekday" specifies the day of the week for each observation.

Particularly, the "posture" column delineates the pig's stance into distinct states: 0 signifies "Lateral Right Lying", 1 corresponds to "Lateral Left Lying", 2 denotes "Sitting", 3 represents "Standing", and 4 indicates "Sternal Lying". And “Sternal Lying”' means the pig lying down and the chest of a pig touching the ground as the picture below. This classification offers insights into the different positions assumed by the pigs throughout the observation period.

## How to use
Kmeans Analysis -> `kmeans.iypnb`
Subgroup Analysis -> `subgroup_analysis.ipynb`
Chloe traditional classifier -> `./chloe_trad_classifier`