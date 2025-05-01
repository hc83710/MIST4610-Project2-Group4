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
How do mortality trends for COVID-19 and Influenza & Pneumonia compare across different states from 2020-2023?

![image](https://github.com/user-attachments/assets/3d06f021-dcbc-48db-81d6-0db09d83f34b)


We chose to represent this question visually through two bar graphs. Each bar is one of the fifty states and each year is represented by a different color on each bar.

The comparison of COVID-19 and Influenza & Pneumonia mortality trends across states from 2020 to 2023, as represented in the graph, is an important question because it highlights variations in public health outcomes during overlapping pandemic years. A critical factor of this question lies in understanding the social determinants of health and their role in shaping public health outcomes. Geographic disparities in mortality rates can highlight how systemic factors—such as socioeconomic status, access to healthcare, and regional public health infrastructure—affect different populations. For example, according to an article by the CDC, areas with higher poverty levels and lower access to healthcare experienced disproportionate impacts during the COVID-19 pandemic, with mortality trends reflecting these inequalities​. This question overall is socially significant because it sheds light on how systemic inequalities manifest geographically, impacting not just COVID-19 outcomes but also co-occurring illnesses like influenza and pneumonia, which share similar pathways in affecting vulnerable populations. 

This question is particularly interesting as it underscores potential disparities among states, which may relate to healthcare access, population density, policy differences, or public health responses during these years. Observing patterns such as higher mortality rates in certain states or notable changes from year to year can guide discussions about resource allocation, preparedness for respiratory illnesses, and long-term health strategies. Understanding such trends can provide insights into areas most impacted and inform strategies to mitigate future mortality rates.

## Question 2
What are the top five causes of death for the Southeast region compared to the United States, and how have these trends evolved over the years?

![image](https://github.com/user-attachments/assets/19927928-f7dd-417f-b62f-8e76691c2d05)


We visualized this question through two line graphs combined through the Dashboard feature on Tableau; the top graph represented the Southeast region and the bottom graph represented the United States. The top five causes were natural causes, diseases of the heart, malignant neoplasms, COVID-19 as a multiple cause of death, and COVID-19 as an underlying cause of death. The states we included in the Southeast region were Alabama, Florida, Georgia, Mississippi, North Carolina, South Carolina, and Tennessee. 

This question is important because identifying evolving patterns in causes of death can help in strategizing future healthcare policies. Healthcare professionals can understand the most prevalent causes of death and work towards advancing healthcare to lower these numbers. The American Heart Association discusses some of the advances made in the year of 2023 to held reduce the risk of cardiovascular diseases. For example, healthcare professionals are working with a new drug would help prevent the presence of hypertension which could consequently lower the number of heart attacks. Advances such as these could explain why we are seeing a downward trend in mortality rates. Separating the data by region adds interest to the question as it allows us to identify any difference between different parts of the United States.

## Manipulations
For our second question, we decided to only focus on the top five causes of mortality and filtered out the other nine causes. The mortality rates for the excluded nine causes were incredibly similar, and we found that this made our graphs look messy and hard to read. By only showing the top five causes we could understand the graph better and make better conclusions based off the results.

## Analysis and Results
In terms of question one, we can see that mortality trends for both diseases are declining, reflecting the impact of public health interventions (e.g. vaccines and awareness campaigns). Mortality rates are higher in densely populated states and lower in states with fewer people, emphasizing regional differences. California, Florida, and Texas had the highest mortality rates for both causes and this could be attributed to their population size. According to the Population Reference Bureau, in 2020, California, Florida, and Texas have the highest populations for those over the age of 65, which can explain why these trends appear in the visualizations. COVID-19 is a novel virus, resulting in much higher mortality rates across all states. Influenza is a seasonal diseases with established vaccines and treatments, leading to lower or zero mortality in some states.

For our second question, natural causes maintain the leading causes of mortality throughout 2020-2023. COVID-19 spikes in 2020 and 2021, but tapers off in 2022 and 2023. Regardless, the deaths from natural causes, heart diseases, and malignant neoplasms were still higher than deaths from COVID-19. Diseases of the heart and malignant neoplasms (cancerous tumors) showed relatively consistent patterns over the course of the four years yet continued to be significant contributors to overall mortality. For each cause of death, there was a downward trend from 2023-2024, which could indicate better healthcare and a higher quality of overall health. The gap between COVID-19 deaths and other causes of death began to widen from the end of 2021 to 2023, which again could show the progress made on handling the pandemic within the country. In terms of the Southeast region itself, the trends within the region reflected the trends within the United States very similarly. The number of deaths in the Southeast made up around 10% of the deaths in the United States. 

## Sources
(https://www.cdc.gov/pcd/issues/2022/21_0414.htm)
(https://www.heart.org/en/around-the-aha/aha-names-top-advances-in-cardiovascular-disease-research-for-2023)
(https://www.prb.org/resources/which-us-states-are-the-oldest/)
