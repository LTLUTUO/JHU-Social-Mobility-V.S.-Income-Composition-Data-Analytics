# JHU-Social-Mobility-V.S.-Income-Composition-Data-Analytics
### Description
In both China and the US, people are talking about sexism (sex-based discrimination), urging others to change and take actions. In the same time, some parents in China let their children to have their own businesses in other city, while others doesn't. In this analytic resreach, I find out that the **household income from female** across all the percentile of parents' income in both New York and Baltimore **are higher** than **household income from male**. Also, the **posibility** of people staying in the same city **decreases as** the percentile of **parents' income increases**.
![alt text](https://github.com/LTLUTUO/jhu-social-mobility-data-analytics/blob/master/%25%20of%20Income.png)
![alt text](https://github.com/LTLUTUO/jhu-social-mobility-data-analytics/blob/master/Table%201.png)
### Research Focuses
* How is the **composition** of the household income in Baltimore and New York across the percentile of parents' income; 
* What is the **posibility** of people staying in the same city across the percentile of parents' income; 
* what is the **relationship** of the two problems above. 
### Research Method
* The source data.csv for **[household income](https://drive.google.com/open?id=18thxiin5Coch_dJB2bPFJEFt-wvZPcbE)** and **[city population movement](https://drive.google.com/open?id=1r8nIoU-54hhI21YRFsSDj3o6LNqZMtCW)** are extracted from [The Opportunity Atlas](https://www.opportunityatlas.org/). Then some classification for the source data are done to the .csv. For example, through searching, I found out that the city code inside the tracts for New York is 360, and the city code for Baltimore is 245. Thus, I extracted the citycode from the tracts code, and sorted them by the code.
* Then I created a **[formatted excel](https://drive.google.com/open?id=1EwI1hCwHIGekl9HoPNVxq5DZmFLGRixs)** to consolidate the information from both .csv. During the process, Vlookup is being used for a lof of time, along with If. After that, a consolidated table for calculation is created.
* At last, Two pivot tables are created to enable the making of two charts.
### Component
* [household income.csv](https://drive.google.com/open?id=18thxiin5Coch_dJB2bPFJEFt-wvZPcbE)
* [city population movement.csv](https://drive.google.com/open?id=1r8nIoU-54hhI21YRFsSDj3o6LNqZMtCW)
* [formatted excel.xlsx](https://drive.google.com/open?id=1EwI1hCwHIGekl9HoPNVxq5DZmFLGRixs)
### Reference
* [The Opportunity Atlas](https://www.opportunityatlas.org/)
* [Lecture from Data Analytics](https://docs.google.com/presentation/d/1xdsb4yoo8g5ccGGfVDLLO0cm_WWsHqwoU2rMjqr951E/edit#slide=id.g76b6f65729_0_529)
* [Formatting Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
