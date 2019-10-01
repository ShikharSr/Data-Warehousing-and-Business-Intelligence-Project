# Analysis of Cyber threats by Proportion of Online Population
In this project 4 different data sources were integrated together in a star schema from scratch after which few BI queries were formulated and answered. R was used for web scraping while SSIS and SSAS were used for ETL, cubes respectively. Data was visualized in excel.

## Data Sources Used: ##

| Source        | Type          | Brief Summary  |
| ------------- |:-------------:| :-----:|
| Abuseipdb.com      | Semi-Structured | Semi-Structured Malicious IPs are extracted from this data source |
| Internetworldstats.com      | Structured      |   Country wise internet users are present here |
| Comparitech.com | Unstructured      |    Top countries based on 7 factors extracted from an image present here |
| Statista | Structured      |    LATAM countries by internet users |

Abuseipdb.com ---- https://www.abuseipdb.com/sitemap?page=1
 
Internetworldstats.com ---- https://www.internetworldstats.com/stats4.htm#europe   ,   https://www.internetworldstats.com/stats3.htm#asia , 
https://www.internetworldstats.com/stats1.htm


Compritech.com ---- https://cdn.comparitech.com/wp-content/uploads/2017/02/Countries-that-are-the-Most-and-Least-Cyber-Safe-final.jpg

Statista ---- https://www.statista.com/statistics/186919/number-of-internet-users-in-latin-american-countries/


## Data Model and ETL Process is explained in detail in the project document.
