# Web Visualization Dashboard(Latitude)


## Background

![alt text]()

The global human population reached 8 billions from an estimated 2.5 billion people in 1950. As the living space on the Earth is limited, human beings are getting more pressures from shrinking living spaces. 

We saw an experiment “Universe 25, 1968-1973” which is a series of rodent experiments that showed that even with abundant food and water, personal space is essential to prevent societal collapse. Although some people think the experiment was rigorous and human social networks are not like rodent animals’, we still do notice some similar phenomenon found in Universe 25 happening in our society.

We scraped three data sets from the world bank, population by nations, GDP by nations, and sex distribution by nations.


## Source

The three data sets come from https://data.worldbank.org/. 

## Brainstrom

1. Does the national population grow when GDP increases?  
2. As national borders are almost the same as the past 30 years, does the population increasing rate slow down as time passes? How about GDP?  
3. When GDP increases or the number of national population increases, does sex ratio change?  
4. Five continents have their own unique climate and geological conditions, does it matter?  



## Process

Extracting:  
We plan on extracting 2 separate csv files from the World Bank website. One relating to each country's population and the other to do with each country's GDP.  

Transforming Data:  
We plan on restricting both datasets to the last 10yrs of data to keep it relevant. We will also filter out any null values or both datasets.  

Load:  
We plan on displaying these merged datasets as tables on postgreSQL.   



## Content:
```
Project  
├── Images
│   ├── comparison-lg.png
│   ├── comparison-sm.png
│   ├── data-lg.png
│   ├── data-sm.png
│   ├── landing-sm.png
│   ├── landingResize.png
│   ├── nav-lg.png
│   ├── nav-sm.png
│   ├── visualise-lg.png
│   └── visualise-sm.png
├── README.md
├── Resources
│   ├── CityData.csv
│   └── CityData.html
├── assets
│   ├── css
│   │   └── style.css
│   └── images
│       ├── LatCloud.png
│       ├── LatHumi.png
│       ├── LatMaxt.png
│       └── LatWindSd.png
├── index.html
└── visulisations
    ├── Cloudiness.html
    ├── Comparisons.html
    ├── Humidity.html
    ├── Max Temperature.html
    └── Wind Speed.html

```



## Reference

1. https://cosmosmagazine.com/science/mathematics/calhoun-rodent-experiments/  
2. https://www.the-scientist.com/foundations/universe-25-1968-1973-69941  
3. https://www.google.com.au/url?sa=t&source=web&cd=&ved=2ahUKEwjg_9qvqLD6AhXD7zgGHTTkCysQFnoECAUQBg&url=https%3A%2F%2Fdesapublications.un.org%2Ffile%2F989%2Fdownload&usg=AOvVaw0LKWr15IBA0_ojeoky-FfW  
