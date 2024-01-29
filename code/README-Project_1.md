### Overview

This Project look at data from World Development Statistics from [Gapminder](https://www.gapminder.org/about/), an independent Swedish foundation that aims to make data about the world more accessible and reliable. From their data, a problem statement and various insight was developed. A good introduction on Gapminder is this [Ted Talk](https://www.ted.com/talks/hans_rosling_the_best_stats_you_ve_ever_seen) from Hans Rosling, which also shows how effective data visualization can be for your audience.


### Problem Statement


**Investigating the Relationship Between Economic Resources and Life Expectancy to Inform Strategic Decision-Making**

---


#### Provided Data

The dataset that will be choosen for analysis will be **gni_per_cap_atlas_method_con2021.csv** and **life_expectancy.csv.**

**gni_per_cap_atlas_method_con2021.csv** "GNI per capita" stands for Gross National Income per capita. The dataset has information to assess the average economic output per person in a country. The columns has the year from 1800 to 2050 and rows of the countries. GNI per capita is a useful metric for understanding the average economic well-being of the citizens of a country. Higher GNI per capita generally indicates a higher standard of living, while lower GNI indicates a lower standard of living.

**life_expectancy.csv.** dataset includes information about life expectancy at birth for different countries. The columns that are present in the dataset are Countries (Names identifying the countries for which life expectancy data is reported) and the Year (the year for which life expectancy data is recorded). The values shows the average number of years a newborn can expect to live, usually measured at birth.

---

### Data dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|country|object|Merged| Name of the countries (Japan, United Kingdom, and Nigeria selected)
|year_gni|int|Merged|Gross National Income for the specifed year (2000 -2024)
|year_life|float|Merged|Life expectency for the specified year (2000 - 2024)

---

#### Brief summary of your analysis

The consistency in correlation values across GNI and life expectancy from the data for different years suggests that the relationship is robust and not limited to a specific time period. Moreover, the strong and increasing positive correlation between GNI and Life expectancy highlight the potential importance of economic development in influencing the well-being and longevity of populations, which is a good advocate for sustainable development goals 


---

### Conclusions/recommendations

This project looked at investigating the relationship between economic resources and life expectancy to inform strategic decision-making on sustainable development goals. The correlation analysis done in the exploratory data analysis phase provides a quantitative measure of the relationship between GNI and life expectancy for countries of Nigeria, Japan and United Kingdom. The information found in this project is valuable to key stakeholders in any vertices who seek to understand the degree to which economic resources are correlated to life expectency.

The robust and increasing positive correlation indicates that as economic resources (GNI) increase, life expectancy tends to increase as well. This statement put forwards actionable insight that can be crucial for decision-makers, for the reason that it proposes that investments in economic development may have positive implications for the health and longevity of the population. 

Managers, Lawmakers, and CEO who has interest in and want to justify their economic development initiatives, would be able to make more informed decision regarding resource allocation, investment and strategic planning with presentation of the data in this project. For example, if there is a sudden drop in economic indicators, decision-makers can anticipate potential impacts on public health and take proactive measures. Moreover, lawmakers can use the insight taken from this data to formulate evidence based laws that promote economic and health-related goals. CEO and other key decision makers who works in healthcare could use this insight to justify efforts to improve healthcare system. 

Further recommendation of research can be found in the work done by Nandi et al.,(2023) where he stated that GNI, employment rate, and age dependency ratio are the top determinants of life expectancy (LE). The growth of Gross National Income and employment facilities can contribute to decreasing the age dependency ratio and increasing the LE (Nandi et al., 2023). The insight dereived from this work and this project advocates for sustainable development goals that is a call to action to end poverty and inequality, protect the planet, and ensure that all people enjoy health, justice and prosperity (Sustainable Development Goals, 2023).



---

### Resources

International Monetary Fund GDP per capita 2019, United Nations Human Development Report 2019

Nandi, D. C., Hossain, Md. F., Roy, P., &amp; Ullah, M. S. (2023). An investigation of the relation between life expectancy &amp; socioeconomic variables using path analysis for Sustainable Development Goals (SDG) in Bangladesh. PLOS ONE, 18(2). https://doi.org/10.1371/journal.pone.0275431 

Reuell, P. (2016, April 11). For life expectancy, money matters. Harvard Gazette; Harvard Gazette. https://news.harvard.edu/gazette/story/2016/04/for-life-expectancy-money-matters/

Selvanathan, M. (2020, October 28). The scale of Pearson’s Correlation Coefficient. ResearchGate; ResearchGate. https://www.researchgate.net/figure/The-scale-of-Pearsons-Correlation-Coefficient_tbl1_345693737

Sustainable development goals. (2023, November 16). https://www.who.int/europe/about-us/our-work/sustainable-development-goals#:~:text=The%20Sustainable%20Development%20Goals%20(SDGs,no%20one%20is%20left%20behind.

---

