# Introduction
[Bey Wheels](https://en.wikipedia.org/wiki/Bay_Wheels) is a regional public bicycle sharing system in California's San Francisco Bay Area. Operated by Motivate in partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District, the system launched as Bay Area Bike Share in August 2013. At launch, it was the West Coast’s first regional bike-share network and the first in the U.S. to serve a multi-city region rather than a single city or a pair of adjacent cities.
In June 2017, the system was officially relaunched as Ford GoBike in a partnership with [Ford Motor Company](https://en.wikipedia.org/wiki/Ford_Motor_Company).

# fordgobike-system-data
Ford GoBike System Data Analysis and Exploration
As part of Udacity’s Data Analyst Nanodegree, I used Python data science and visualization libraries to explore the dataset, examining its structure, anomalies, patterns, and relationships.

# Summary of Findings
1. Average trip times
2. Monthly bike ride trend and average trip times
3. Average trip times by gender.


I began by examining the dataset’s structure, focusing on factors that influence trip duration.

This dataset is from the Ford GoBike System data (a bike rental company), with 5054 bikes in this dataset with 1,863,721 rows and 12 features.

Data wrangling involved converting the source files, consolidating 12 monthly datasets into a single annual dataset, and dropping unused columns to streamline the analysis.

During exploration, I observed a relationship between trip counts and average duration: the overall average was just under 10 minutes, with some trips exceeding 300 minutes. Throughout the year, the monthly minimum number of trips stayed relatively high, never dropping below ~200. June and July had the longest trips, while January and December saw fewer long rides; shorter trips occurred year-round. Adding gender showed female users consistently had shorter trips than males, with female durations increasing in June through August. Male users’ trips were consistently longer and, in some months, averaged above 400 minutes.
