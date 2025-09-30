# Seattle Weather Project - DATA 5100
Project 1 by Alyssa Zukas

Comparing the precipitation rate of Seattle to another city in the US.
    In class comparison:St Luis
    Personal project comparison: Bentonville, AR

---

## Project Overview

We will use this project to compare the preciption levels of Seattle vs another city.

- **Objective:** Clearly state the main goal of the project.
- **Domain:** (e.g., Healthcare, Finance, E-commerce, etc.)
- **Key Techniques:** (e.g., Regression, Classification, Clustering, NLP, Time Series)

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:**
- Bentonville:
        http://localhost:8888/doc/tree/data5100/weather/data/bentoville_weather.csv?
        https://github.com/alyzukas/weather/blob/main/data/bentoville_weather.csv
- Seattle:
        http://localhost:8888/doc/tree/data5100/weather/data/seattle_rain.csv?
        https://github.com/alyzukas/weather/blob/main/data/seattle_rain.csv
- St Louis:
        http://localhost:8888/doc/tree/data5100/weather/data/stl_rain.csv?
        https://github.com/alyzukas/weather/blob/main/data/stl_rain.csv
      
- **Description:** 
Bentonville:
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 1824 entries, 0 to 1823
Data columns (total 4 columns):
 #   Column   Non-Null Count  Dtype  
---  ------   --------------  -----  
 0   STATION  1824 non-null   object 
 1   NAME     1824 non-null   object 
 2   DATE     1824 non-null   object 
 3   PRCP     1824 non-null   float64
dtypes: float64(1), object(3)
memory usage: 57.1+ KB

Seattle:
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 1658 entries, 0 to 1657
Data columns (total 10 columns):
 #   Column   Non-Null Count  Dtype  
---  ------   --------------  -----  
 0   STATION  1658 non-null   object 
 1   NAME     1658 non-null   object 
 2   DATE     1658 non-null   object 
 3   DAPR     23 non-null     float64
 4   MDPR     23 non-null     float64
 5   PRCP     1636 non-null   float64
 6   SNOW     353 non-null    float64
 7   SNWD     66 non-null     float64
 8   WESD     15 non-null     float64
 9   WESF     28 non-null     float64
dtypes: float64(7), object(3)
memory usage: 129.7+ K


St Louis:
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 54574 entries, 0 to 54573
Data columns (total 8 columns):
 #   Column   Non-Null Count  Dtype  
---  ------   --------------  -----  
 0   STATION  54574 non-null  object 
 1   NAME     54574 non-null  object 
 2   DATE     54574 non-null  object 
 3   DAPR     1166 non-null   float64
 4   MDPR     1163 non-null   float64
 5   PRCP     53143 non-null  float64
 6   SNOW     33167 non-null  float64
 7   SNWD     12835 non-null  float64
dtypes: float64(5), object(3)
memory usage: 3.3+ MB


- **License:** N/A

---

## Analysis

Describe the notebooks and/or scripts used to perform the analysis. Specify the order in which the code should be run to reproduce the results.

---

## Results

Include a short discussion of the findings and what they imply.

---

## Authors

- Your Name - [@alyzukas](https://github.com/alyzukas)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used
- Tutorials or papers referenced
- Inspiration or collaborators
