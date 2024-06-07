# EDA-with-Python
### Unveiling the Story Behind the Summer Olympic Games
### OVERVIEW
In the pursuit of uncovering the rich history and patterns of the Summer Olympic Games, our team embarked on an analytical journey using powerful Python libraries such as NumPy, Pandas, Seaborn, and Matplotlib. Through meticulous data cleaning, in-depth analysis, and insightful visualizations, we aimed to reveal the hidden stories of the participants, events, and outcomes that have shaped the games over the years.

### Data Sources 
https://www.kaggle.com/datasets/nitishsharma01/olympics-124-years-datasettill-2020

### Our analysis hinged on two primary datasets:
  
- Athletes Summer Games Data: This dataset provided comprehensive details about the athletes, their teams, the sports they competed in, and the medals they won.
- Regions Data: This dataset offered crucial regional information associated with each team, enriching our understanding of the global participation in the games.
  
### Data Cleaning and Preparation

Our first step was to get acquainted with the datasets:
- We inspected the initial records, checked data types, summary statistics, and identified any null values and duplicates.
Next, we focused on cleaning the regions data.
- We dropped rows with missing values and removed unnecessary columns to streamline the dataset.
- After ensuring no remaining null values or duplicates, we merged this cleaned data with the athletes' data using the National Olympic Committee (NOC) codes, creating a comprehensive dataset ready for analysis.

### KEY ANALYSIS AND FINDINGS
### Participation Analysis:
- Total Teams: We identified the number of unique teams that participated in the games.
- Sporting Activities: We counted the distinct sports contested.
- Gender Participation: We analyzed the number of male and female participants, highlighting the gender dynamics of the games.
### Medal Analysis:
- Total Medals: We calculated the total number of medals awarded across all games.
- Top and Bottom Teams: We identified the teams with the highest and lowest medal counts, showcasing the competitive landscape.
- Yearly Analysis: We determined the year with the highest number of medals won, marking significant moments in Olympic history.

 ### City and Player Analysis:
- City Participation: We found the city that participated the most over the past 124 years, illustrating the geographical hotspots of the Olympics.
- Top Player: We identified the individual player who won the highest number of medals, celebrating outstanding athletic achievements.
- Host Regions: We determined which regions hosted the most games, reflecting on the global spread and reach of the Olympics.

### Visualization and Additional Insights
To bring our findings to life, we created several visualizations:
- Host Cities Visualization: We visualized the cities that hosted the Olympics over the years, showing the frequency and distribution.
- Olympic Games Count: We counted the number of games held and visualized the distribution of sports, providing a clear view of the evolution of the games.
- Team and Region Visualization: We created a count plot to show the distribution of teams by region, emphasizing the global diversity.
- Average Age Analysis: We calculated and visualized the average age of male and female players, offering insights into the demographics of the athletes.
- Top and Bottom Teams: We listed the top 10 and bottom 10 teams based on medal counts, highlighting the leaders and underdogs in Olympic history.

### Visualizations
- Bar Plot of Host Cities: This plot showcased the frequency of cities hosting the Olympics, revealing popular host locations.
- Bar Plot of Sports: We displayed the distribution of various sports, illustrating the variety and popularity of different events.
- Count Plot of Teams by Region: This plot illustrated the relationship between teams and their regions, highlighting the global participation.

## Conclusion
Our project successfully unraveled various aspects of the Summer Olympic Games, providing valuable insights into participation trends, gender distribution, medal counts, and hosting patterns. The visualizations enriched our understanding, offering a clear and compelling view of Olympic history.
As we reflect on these findings, there is ample opportunity to delve deeper, incorporating more detailed metrics or comparing with additional datasets to uncover further insights into the impact and evolution of the Olympic Games. The story of the Olympics is one of global unity, fierce competition, and extraordinary achievements, and our analysis sheds light on these enduring themes.
