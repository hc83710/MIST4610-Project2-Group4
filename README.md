# MIST4610-Project2-Group4

## Team Name: 
61608 Group 4

## Team Members:
1. An, Ben [@benan03](https://github.com/benan03)
2. Burt, Keegan[@keeganburt24](https://github.com/keeganburt24)
3. Cheng, Hsin [@hc83710](https://github.com/hc83710)
4. Cho, Nick [@nichooo4](https://github.com/nichooo4)
5. Shields, David [@DubNation44](https://github.com/DubNation44)

## Dataset Overview
Our chosen dataset is titled "Crime Data from 2020 to Present", and it was obtained from the Los Angeles Police Department via Data.gov. The dataset records crime incidents reported by the LAPD beginning in 2020 and is updated on a bi-weekly basis. It includes data from original paper reports, which may contain minor inaccuracies or incomplete fields due to system transitions and reporting delays.

The dataset features a variety of useful fields such as the case number (DR_NO), the date the crime occurred (DATE OCC), the geographic area where the crime took place (AREA NAME), the type of crime (Crm Cd Desc), and whether a weapon was used (Weapon Desc). Additionally, geolocation information is provided through latitude and longitude fields (LAT, LON), enabling spatial analysis of crime patterns across Los Angeles.

Through this information, we were able to analyze crime distribution and trends, examine the frequency of violent incidents, and explore how external factors—such as shifts in police funding—may have influenced overall crime rates in Los Angeles over the past five years.

## Question 1
Where should LAPD send more officers to reduce crime?

![image](https://github.com/user-attachments/assets/f698af42-4959-4e09-add2-3657cc9b3c6c)

![image](https://github.com/user-attachments/assets/3664b1c1-525c-4c03-b365-07ae19843162)


We chose to explore this question visually using a heatmap and a bar graph that illustrate the density and location of violent crimes across Los Angeles regions. The central focus of this analysis is to determine where LAPD resources—particularly patrol officers—can be deployed most effectively to reduce crime. Violent crimes such as murder, manslaughter, rape, robbery, and aggravated assault were prioritized, as these incidents have the most immediate and serious consequences for public safety.

The heatmap shows clusters of high crime density, particularly in certain central and southern areas of LA. These regions are highlighted in dark red, signaling a greater concentration of violent crime. The accompanying bar chart titled "Number of Crimes per Square Mile by Region" identifies Central LA as having the highest crime rate, followed by regions like 77th Street, Southwest, and Southeast. These visuals together provide a strong case for reallocating or increasing officer presence in these high-density zones to deter crime, respond faster, and increase community protection.

This question is important because LA has one of the highest crime rates among major U.S. cities, and efficient allocation of law enforcement is key to resource management. Understanding where violent crime is concentrated allows law enforcement to act strategically rather than reactively. Ultimately, this question helps guide smarter decisions in policing and promotes a more data-driven approach to public safety.



## Question 2
Has Defunding the Police Affected Crime in LA?

<img width="675" alt="Screenshot 2025-04-30 at 9 51 00 PM" src="https://github.com/user-attachments/assets/9f045c9c-a61d-4483-b637-28590d8961f1" />

To explore the impact of recent police budget changes, we asked: Has defunding the police affected crime in Los Angeles? This question is especially relevant given the national conversation around policing and public safety reform following 2020.

We visualized this question using a line graph created in Tableau, which displays the annual number of reported crime cases in Los Angeles from 2020 to 2024. The graph focuses on the four LAPD areas with the highest cumulative crime counts: Central, 77th Street, Pacific, and Southwest. By filtering the dataset to include only these regions and organizing the results by year, we were able to observe meaningful patterns in crime trends.

This question matters because understanding how crime rates have evolved in the wake of police budget changes can help guide future resource allocation and public safety strategies. From 2020 to 2022, crime increased significantly in each of the four areas, possibly due to reduced police presence, broader social unrest, or pandemic-related factors. However, from 2023 to 2024, we observed a sharp decline in crime rates across all regions. This reversal may reflect delayed effects of earlier reforms, adjustments in police deployment strategies, or improvements in community-based safety initiatives.

By focusing on high-crime regions and tracking these shifts over time, this analysis provides valuable insights for policymakers, law enforcement, and local communities seeking to strike a balance between public safety and social justice.

## Manipulations
For our second question, we applied a few key filters to help clarify trends and focus our analysis. 

Specifically, we chose to include only the four LAPD divisions with the highest total crime counts: Central, 77th Street, Pacific, and Southwest, by filtering the "Area Name" column. Including all 21 areas would make the visualization cluttered and difficult to interpret, so narrowing the focus helped emphasize the areas most relevant to our research.

We also restricted the data to crime cases reported to the time range between 2020 and 2024 by filtering the "Year" of "Date Occ" column. This allowed us to examine crime trends during a time period when discussions around police funding were most prominent. These manipulations help make the line graph cleaner and the trends more distinct, enabling us to draw more meaningful conclusions about potential shifts in crime related to police defunding.

## Analysis and Results


(((((((((((((In terms of question one, we can see that mortality trends for both diseases are declining, reflecting the impact of public health interventions (e.g. vaccines and awareness campaigns). Mortality rates are higher in densely populated states and lower in states with fewer people, emphasizing regional differences. California, Florida, and Texas had the highest mortality rates for both causes and this could be attributed to their population size. According to the Population Reference Bureau, in 2020, California, Florida, and Texas have the highest populations for those over the age of 65, which can explain why these trends appear in the visualizations. COVID-19 is a novel virus, resulting in much higher mortality rates across all states. Influenza is a seasonal diseases with established vaccines and treatments, leading to lower or zero mortality in some states.

For our second question, natural causes maintain the leading causes of mortality throughout 2020-2023. COVID-19 spikes in 2020 and 2021, but tapers off in 2022 and 2023. Regardless, the deaths from natural causes, heart diseases, and malignant neoplasms were still higher than deaths from COVID-19. Diseases of the heart and malignant neoplasms (cancerous tumors) showed relatively consistent patterns over the course of the four years yet continued to be significant contributors to overall mortality. For each cause of death, there was a downward trend from 2023-2024, which could indicate better healthcare and a higher quality of overall health. The gap between COVID-19 deaths and other causes of death began to widen from the end of 2021 to 2023, which again could show the progress made on handling the pandemic within the country. In terms of the Southeast region itself, the trends within the region reflected the trends within the United States very similarly. The number of deaths in the Southeast made up around 10% of the deaths in the United States. ))))))))))))))

## Sources
(LAPD OpenData. Crime Data from 2020 to Present. Data.gov, updated April 19, 2025, https://catalog.data.gov/dataset/crime-data-from-2020-to-present. )
