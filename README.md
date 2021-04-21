# Project of Data Visualization (COM-480)

| Student's name | SCIPER |
| -------------- | ------ |
| Berger Thomas | 287838 |
| Bouquet Pierre | 282916 |
| Walt Eliot| |

[Milestone 1](#milestone-1) • [Milestone 2](#milestone-2) • [Milestone 3](#milestone-3)

## Milestone 1 (23rd April, 5pm)

**10% of the final grade**

### Dataset

Our work will focus on the "Formula 1 World Championship (1950 - 2021)" dataset extracted from [Kaggle](https://www.kaggle.com/rohanrao/formula-1-world-championship-1950-2020).

The dataset contains all the information about races, drivers, circuits and constructors over more than 70 years of racing. Adiitionnally, the data set contains all the points received after each race by the drivers and the constructors. Furthermore, for some years it even contains all the  qualifying (1994-2021), lap-times (1996-2021), pit-stops (2011-2021) informations.<br>
The dataset is already clean and ready to use, a data exploration will be needed to get a grasp on how the data is organised and what visualisation is possible to achieve.
 

### Problematic

The main aspect we would like to show with our visualisation is the gigantic history of Formula 1 racing. We want the general public to get a grasp on how Formula 1 evolved through time, and discover more details about the tracks and how performance is always increasing.<br>
We also want the "hardcore" fan to be able to explore history of racing discovering interesting fact they didn't know. By analysing past seasons or races or checking pilots summary.

Therefore we think about multiple views we would like to cover.
 - Geographic positions and evolution of tracks through time.
 - Details about tracks ( SVG, best lap-times through history , ...)
 - Past seasons overview (Driver standings, constructors standings, race locations)
 - Details about pilots and constructors (evolution through years)
 - Details about every grand prix (Podium, time deltas, best lap, ...)

The main idea is to be able to see general data allowing you to understand general history of F1 and be able to dive in really precise points you want to know about.

The main schematic is to have a page containing a time range and and world map with all circuits locations during this time range.<br>
<p align="center">
<img src="/Images/Main_view.jpeg" width="50%" >
</p>

 - By clicking on a certain object the page will transform to view the object selected on the linked time range. <br>You can click on a circuit (on the map), on a pilot or on a team (on the second view)<br>
<p align="center">
<img src="/Images/Stat_View_time_range.jpeg" width="50%" >
</p>

 - By clicking on a specific date you can view the pilots standing for this season, the constructors standing for this season and details about this specific Grand Prix.<br>The pilot and constructor standing should be clickable and bring you to the detailed view of one pilot/constructor over the linked time range.<br>
<p align="center">
<img src="/Images/Stat_View_specific_time.jpeg" width="50%" >
</p>

### Exploratory Data Analysis

We explored the dataset in this [Jupyter Notebook](/Milestone_1/Exploratory_Data_Analysis.ipynb) using mainly the pandas library.  

### Related work


> - What others have already done with the data?
> - Why is your approach original?
> - What source of inspiration do you take? Visualizations that you found on other websites or magazines (might be unrelated to your data).
> - In case you are using a dataset that you have already explored in another context (ML or ADA course, semester project...), you are required to share the report of that work to outline the differences with the submission for this class.

## Milestone 2 (7th May, 5pm)

**10% of the final grade**


## Milestone 3 (4th June, 5pm)

**80% of the final grade**


## Late policy

- < 24h: 80% of the grade for the milestone
- < 48h: 70% of the grade for the milestone

