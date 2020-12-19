# Project-11---Explanatory-Data-Analysis-and-Seaborn-Visualization-Olympic-Games-
The purpose of this project is to gather Olympic data to analyze(explanatory data analysis), clean, merge and visualize with Seaborn.

__The main questions this project will focus on are__: 
1) What countries have been given the most medals in the Winter and Summer Olympics? 
2) What countries have the highest rankings? 
3) Why are some countries more successful than other countries? 

__Method__:
1)Import the data / First Inspection
2)Merging and concatenating
3)Data cleaning
4) visualize data 

Results 

1) Import Data / First Inspection 

- Missing values from countries due to name changes or countries do not exist anymore. Country codes also have changed or become outdated. 
- Both summer and winter datasets use the same columns (easy to concatenate later)
- Some athlete data is pending 
- Data types are correct for given values 


2) Merging and Concatenating 

- Vertical concatenate
- Left join

Concatenating points:
- Summer and Winter data have the same 9 columns which make it easy to concatenate.


3) Data Cleaning 
- Rename column labels as there are blank spaces between labels and unintuitive labels 
- Update missing values with appropriate country names
- Filter out missing values 


Q: What are the most succsseful countries?

United States     5238
Soviet Union      2489
United Kingdom    1799
Germany           1665
France            1548
Italy             1488
Sweden            1477
Canada            1274
Australia         1204
Hungary           1091


-USA is the highest ranking country collectivaly with 14% overall winnings of medals.
-Soviet Union is 2nd ranked country collectivaly with 6% overall winnings of medals.
-USA has the most gold, silver and bronze medals won(winter / summer medals combined) than any other country. 
-Some countries perform well in the Summer games but poorly in the winter games (refer to graphs for further inspection)
