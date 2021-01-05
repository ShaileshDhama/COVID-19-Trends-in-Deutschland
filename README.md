# COVID-19 Trends in Deutschland

## To analyse and show how covid 19 is spreading differently in the different continent on the earth planet.

**Author** : SHAILESH DHAMA

The 2019 Novel Coronavirus (COVID-19) continues to spread in countries around the world. This dataset provides daily updated number of reported cases & deaths in Germany on the federal state (Bundesland) and county (Landkreis/Stadtkreis) level. In addition, I provide geospatial shape files and general state-level population demographics to aid the analysis.
                
### Dataset :

The dataset consists of two main csv files: covid_de.csv and demgraphics_de.csv. The geospatial shapes are included in the de_state.* files. See the column descriptions below for more detailed information.

covid_de.csv: COVID-19 cases and deaths which will be updated daily.
demographics_de.csv: General Demographic Data about Germany on the federal state level. Those have been downloaded from Germany's Federal Office for Statistics (Statistisches Bundesamt) through their Open Data platform GENESIS.

de_state.*: Geospatial shape files for Germany's 16 federal states. Downloaded via Germany's Federal Agency for Cartography and Geodesy.

## Approach:

### Data processing & Exploratory Data Analysis:

    1.Import Libraries
    2.Load Data
    3.Dataset Exploration
    4.Descriptive Analysis
    5.Visualization
    6.Epidemiology terms: Lethality, Incidence,etc.
    7.Geospatial analysis
    8.Forecasting
           
## RESULTS :

#### Content Distribution
![Content Distribution](./FLIX_1.png)

#### Missing Values in dataset
![Missing Values in dataset](./FLIX_2.png)

#### Movie ratings analysis
![Movie ratings analysis](./FLIX_3.png)

#### Content type on Netflix:
![Content type on Netflix:](./FLIX_4.png)

#### Content added over the years
![Content added over the years](./FLIX_5.png)
![Content added over the years](./FLIX_6.png)

#### Types of Genres
![Types of Genres in Movie](./FLIX_7.png)
![Types of Genres in Series](./FLIX_8.png)

#### Distribution of Movie Rating
![Distribution of Movie Rating](./FLIX_9.png)

#### Distribution of TV Show Rating
![Distribution of TV Show Rating](./FLIX_10.png)

#### Normal distribution for Movies
![Normal distribution for Movies](./FLIX_11.png)

#### Countplot for Seasons in TV_Shows
![Countplot for Seasons in TV_Shows](./FLIX_12.png)

#### Percentage of Seasons in TV_Shows
![Percentage of Seasons in TV_Shows](./FLIX_13.png)

#### Top-10 Genre in Movies
![Top-10 Genre in Movies](./FLIX_14.png)

#### Top-10 Genre in TV Shows
![Top-10 Genre in TV Shows](./FLIX_15.png)

#### Content creating countries
![Content creating countries](./FLIX_16.png)

#### Number of Seasons in Web-Series
![Number of Seasons in Web-Series](./FLIX_17.png)

#### Web-Series with 1 Season
![Web-Series with 1 Season](./FLIX_18.png)

#### Oldest US Web-Series
![Oldest US Web-Series](./FLIX_19.png)

#### Newest US Web-Series
![Newest US Web-Series](./FLIX_20.png)

#### Netflix German Content
![Netflix German Content](./FLIX_21.png)

#### Newest German Web-Series
![Newest German Web-Series](./FLIX_22.png)

#### Content-Based Recommendation System
![Content-Based Recommendation System](./FLIX_24.png)
![Content-Based Recommendation System](./FLIX_25.png)
![Content-Based Recommendation System](./FLIX_26.png)
![Content-Based Recommendation System](./FLIX_27.png)
![Content-Based Recommendation System](./FLIX_28.png)

### For further information:

Please review the narrative of our analysis in [our jupyter notebook](./Netflix%20Recommendation%20System.ipynb)

For any additional questions, please contact **shaileshettyd@gmail.com)

##### Repository Structure:

```

├── README.md                                               <- The top-level README for reviewers of this project.
├── Netflix Recommendation System.ipynb                     <- narrative documentation of analysis in jupyter notebook
├── netflix_titles.csv                                      <- Dataset
└── images                                                  <- generated from code

```
## Citing :

```
@misc{Shailesh:2020,
  Author = {Shailesh Dhama},
  Title = {Netflix Recommendation System},
  Year = {2020},
  Publisher = {GitHub},
  Journal = {GitHub repository},
  Howpublished = {\url{https://github.com/ShaileshDhama/Netflix%20Recommendation%20System.ipynb}}
}
```
