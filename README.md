
# Global Terrorism Analysis


![Logo](https://c4.wallpaperflare.com/wallpaper/208/691/734/counter-strike-counter-strike-global-offensive-game-cg-games-art-wallpaper-preview.jpg)

The Global Terrorism Database (GTD) is an open-source database including information on
terrorist attacks around the world from 1970 through 2017. The GTD includes systematic data on domestic as well as international terrorist incidents that have occurred during this time period and now includes more than 180,000 attacks. The database is maintained by researchers at the National Consortium for the Study of Terrorism and Responses to Terrorism (START), headquartered at the University of Maryland. Explore and analyze the data to discover key findings pertaining to terrorist activities.

We will import NumPy, pandas, matplotlib, seaborn, plotly.express in Google Colab then mount
the drive. After that we will read csv file from working directory path and assigned it into the data
frame called “Terror _Data”.

Data Cleaning is done to remove extra columns and dropping the data not needed. After data cleaning, the data is stored in the data frame name“Terror_Data”. The information consists of, ‘Year’, ‘Month’, ‘Day’, ‘City’, ‘State’, ‘Country’, ‘Region’, ‘Latitude’, ‘Longitude’, ‘Attack
Type’, ‘Target’, ‘Target Type’, ‘Weapon Type’, ‘Killed’, ‘Wounded’, ‘Casualties’, ‘Terrorist
Group’, ‘Motive’, ‘Summary’.

Our dataset contains a large number of null values which might tend to disturb our accuracy hence
we dropped them at the beginning of our project in order to get a better result.

Then Exploratory Data Analysis is done on the datasets to get results. For clear insights, Data
Visualization is also done on the data sets. Correlation analysis is done to compare the data.

## Results

1. The highest number of Terrorist activities took place in the year 2014 with 16903 attacks. The least number of attacks took place in the year 1971 with 471 attacks.

2. In the year 1970, 651 attacks occurred and in the year 2017, 10900 attacks occurred. The percentage of attack increased between 1970 and 2017 is 94%.

3. From Correlation Analysis, both variables, i.e. 'Killed' and 'Wounded' have Low Positive Correlation.

4. The highest number of Attack Type is Bombing/Explosion - 88255. The least number of Attack Type is Hijacking - 651 attacks.

5. The most Target Type by Terrorist is Private Citizens & Property. The second most Target Type is Military and then Police.

6. The most affected country is Iraq - 24636 attacks. The least affected country is Egypt - 2479 attacks. (TOP 20 Countries taken)

7. Middle East and North Africa is the most affected region - 50474 attacks.

8. The most affected city is Baghdad - 9775 attacks. The least affected city is Medellin – 848 attacks.(TOP 15 Cities taken)

9. Taliban is the most active terrorist organization.

10. In the year 1970 to 2000, the terrorist activities were vey frequent. After 2010, we can see the rise of terrorist activity in Middle East and North Africa, South Asia and Sub Saharan Desert.

11. Total number of people killed in each region (TOP 10):-

• Maximum - Middle East and North Africa –137642 people killed.
• Minimum - East Asia - 1152 people killed.

  Total number of people wounded in each region (TOP 10) :-

  • Maximum - Middle East and North Africa – 214308 people wounded.

  • Minimum - Central America and Caribbean - 8991 people wounded.

  Total number of people casualties in each region (TOP 10) :-

  • Maximum - Middle East and North Africa – 351950 people casualties.

  • Minimum - East Asia - 10365 people casualties.

12. Total number of people killed in each country (TOP 10):-
  • Maximum - Iraq - 78589 people killed.

  • Minimum - El Salvador - 12053 people killed.

  Total number of people wounded in each country (TOP 10):-

  • Maximum - Iraq - 134690 people wounded.

  • Minimum - Colombia - 10328 people wounded.

  Total number of people casualties in each country (TOP 10):-

  • Maximum - Iraq - 213279 people casualties.

  • Minimum - Philippines - 22926 people casualties.

13. Total number of people killed in each city (TOP 10):-

  • Maximum - Baghdad - 21151 people killed.

  • Minimum - Aleppo - 2125 people killed.

  Total number of people wounded in each city (TOP 10):-

  • Maximum - Baghdad - 56725 people wounded.

  • Minimum - Mogadishu - 4955 people wounded.

  Total number of people casualties in each city (TOP 10):-

  • Maximum - Baghdad - 77876 people casualties.

  • Minimum - Aleppo - 5748 people casualties.

14. Humanity affected by terrorism worldwide from 1970 to 2017 :-

  • Killed - 411868,

  • Wounded - 523869,

  • Casualties - 935737.





## 🛠 Skills

**Programming Language** :- Python

**Libraries used** :- NumPy, Pandas, Matplotlib, Seaborn, plotly.express


## Author

- [@sourav03dutta](https://github.com/sourav03dutta)





