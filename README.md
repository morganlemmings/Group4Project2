# Group 4 
Group 4 MIST 4610 Project #2

# Team Members
[@morganlemmings](https://github.com/morganlemmings) 
[@melissatran0](https://github.com/melissatran0) 
[@mrb74060](https://github.com/mrb74060) 
[@jasongold3](https://github.com/jasongold3) 
[@clarkfarrell2 ](https://github.com/clarkfarrell2)

 # Data Description
The database, “Juvenile salmon measured fork lengths collected from baited “minnow” traps in Campbell Creek, Alaska”, was obtained through the https://catalog.data.gov/dataset website. The publisher is the US Fish and Wildlife Service. There are 402 rows and 5 columns. The columns consists of: reach_id which identifies each individual fish, whereas the fork describes where specifically in the river the fish was found. The fork length describes the distance from the tip of the fish’s snout to the fork in its tail and the last column describes the species of the fish. In terms of data types, the dates are date type data, fork length is numerical, and the rest is categorical data.

# Question 1
Question 1: What is the average fork length of Chinook vs. Coho salmon across all reaches, and how does it vary by fork (Main Stem, North Fork, South Fork)?

Importance: The average fork length is a strong indicator of fish health, growth rate, and habitat quality. By comparing these two species of salmon, we can identify species-specific habitat use within each fork of Campbell Creek. The different sizes across the Main Stem, North Forth, and South Fork can reveal which areas support growth faster and which areas may be less productive. Differences by location help agencies understand localized habitat conditions, such as food availability, water temperature, or flow differences. Understanding which forks produce larger salmon can guide management strategies that support long-term fishery sustainability. By using this data, we can sustain healthy salmon populations that ensure the continuation of traditional fishing practices and cultural heritage since salmon have a deep cultural significance for Indigenous communities residing in Alaska. 

# Question 2
Question 2: Can we predict the fork length of a salmonid based on the sampling reach and date of capture during the 2021 Campbell Creek study?

Importance: As stated above, fork length is a key indicator for understanding fish health, growth rate, and the quality of the habitat. Being able to predict fork length can reveal spatial and seasonal growth patterns. Predictive models will help identify habitats that produce faster-growing fish. Predictive models also help biologists anticipate when and where salmon will reach key size thresholds. Modeling growth over time will also aid in detecting shifts in timing, such as early or delayed seasonable development due to climate or flow changes. The data for fork length, species, date of capture, and sampling reach are once again the needed variables to answer the predictive analysis question. Reach represents spatial variation, while the date represents temporal variation, making them ideal predictors of growth.

# Manipulations 
To prepare the dataset for analysis in Tableau, several key manipulations were performed to ensure data quality and enable meaningful visualizations. 

Question 1: 


Question 2: To prepare the data for analysis, we first deleted any rows with missing fork length values in Excel so that only valid measurements were used in Tableau. The date field was then set to a continuous format, which allowed us to create line charts and look at changes over time. Fork length values were averaged to reduce the impact of outliers and make comparisons clearer across different reaches and species. We grouped the data by both reach and species so that patterns could be visualized more easily. Trend lines were added to the line charts to show how fork length changed with date, and Tableau displayed the equations and R² values to measure how strong those relationships were. Finally, we used Tableau’s forecasting tool to project fork lengths beyond the study period, adjusting the forecast length and confidence intervals to fit the dataset.
