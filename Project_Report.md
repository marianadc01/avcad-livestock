# AVCAD Final Project - Analysis of livestock activities: geographical patterns
### Created by: Maria Dolgaya (28168) and Mariana Coelho (25605)
### Professor Pedro Segurado
### MSc in Green Data Science, ISA, Portugal

Objectives: 
1) explore how different types of livestock change across the country;
2) how these types of livestock are related with the geographical patterns of socio-economic indicators

**Introduction** – Short introduction to the topic, ending with questions/working hypothesis to be addressed and objective (2 pages max.)

Data analysis and visualization are two important concepts that are increasingly emerging through the years. The first refers to the process of inspecting, cleaning, transforming, and modeling data with the goal of discovering useful information, informing conclusions, and supporting decision-making (Brown, 2014) and the second refers to the process of graphically representing information and data aiming at placing complex data in a visual format to facilitate real-time interpretation. 
With these important processes in mind, it’s possible to get a better understanding of how the way we treat data and how we present it to a certain audience can vary from situation to situation.  For example, an audience composed of scientists is much different than an audience composed of artists. So with this, we can affirm that data analysis and data visualization allows us to tell a coherent story from a certain complex dataset. In this project, that was what we were challenged to do.
Using the National Institute for Statistics (Instituto Nacional de Estatística, INE) database, we were able to extract relevant and complex agro-environmental data and with it, tell a story regarding the agro-environmental occurrences in Portugal.
The topic chosen by me and my colleague was the analysis of livestock activities, taking into consideration the geographical patterns. We were tasked with two main objectives: explore how different types of livestock change across the country and understand and try to explain to our audience how these types of livestock are related with the geographical patterns of socio-economic indicators.
With the foundation of our project in mind, we hypothesize that the types of livestock in Portugal exhibit regional dependencies influenced by environmental and weather conditions, topography, and urbanization levels. Specifically, we believe the geographical distribution of livestock is linked to the natural and socio-economic characteristics of each area. In terms of socio-economic factors, we propose that educational attainment correlates with livestock numbers, as more developed and densely populated regions may focus on industries beyond agriculture and livestock. This suggests that regions with higher education levels and industrial development have lower livestock densities compared to rural, agriculturally-oriented areas. Through this analysis, we aim to analyse the relationships between livestock distribution and Portugal's socio-economic landscapes.

**Database description** – Short descriptive statistics of the database/tables (2 page max.)

The INE (Instituto Nacional de Estatística) database is a comprehensive collection of data that can be used for comprehensive analysis of to various aspects of Portugal's economy, environment and society.
This database consists of 9 important variables: 
- Education (education levels of agricultural populations);
- Workforce (volume of agricultural labour force (AWU) and Type of labour force);
- Production (value per área and total);
- Livestock (number of holdings per species);
- Grasslands (area and number of holdings);
- Temporary crops (area and number of holdings);
- Permanent cultures (area and number of holdings); 
- Spatial resolution (civil parishes);
- and Temporal window (1989-2019).

For this project, we used a dataset sourced from the INE database, which was provided to us by our professor. With the variables in mind, we were able to choose the ones most suitable to our topic and work with the data that was considered relevant for us (Education, Workforce, Livestock and Grasslands). Starting with the provided dataset, we also downloaded (the dataset representing the regions and their codes)[https://smi.ine.pt/Categoriaused], then used OpenRefine for data wrangling, incorporating regional data for Portugal to the main dataset based on the regional codes. Using the Python package Pandas, we merged imported tables and created a dataframe containing variables essential for our analysis. 

**Exploratory data analysis** – This will be the most important chapter, where you will try to tell a coherent history by means of numerical outputs and visualizations (10 pages max.)

**Discussion/Conclusions** – a short discussion/main take home messages/conclusions of the work (2 pages max.).

**References**
