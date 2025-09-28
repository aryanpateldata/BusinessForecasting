1. The Data File in Excel or CSV format (3 points). 

- Data is uploaded as excel file in this folder within this repository 




2. Detailed description of the data. See https://help.osf.io/article/217-how-to-make-a-data-dictionary Links to an external site. for ideas on how to create a good data dictionary. (3 points)

- Created and uploaded detailed data dicionary of the data , uploaded in this folder within this repository


3. Data Collection Methodology (2 points). State how the data is collected, by whom, how often, etc. 

 - Data was collected from https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data/data?select=GlobalLandTemperaturesByCountry.csv . 
The main author / publisher of the data is Berekley Earth . We will be focusing on the GlobalLandTemperaturesByCountry file as it is under 25 mb (the max file size git hub allows and as assignment says we need to submit xlsx or csv , we cannot therefore upload compressed version of the data as zip or parquet).
The data is from 1743 to 2013 , 245 unique countries . Data is recorded at the monthly level. 

 - "From the Kaggle Website - Early data was collected by technicians using mercury thermometers, where any variation in the visit time impacted measurements. In the 1940s, the construction of airports caused many weather stations to be moved. In the 1980s, there was a move to electronic thermometers that are said to have a cooling bias.
Given this complexity, there are a range of organizations that collate climate trends data. The three most cited land and ocean temperature data sets are NOAA’s MLOST, NASA’s GISTEMP and the UK’s HadCrut.
We have repackaged the data from a newer compilation put together by the Berkeley Earth, which is affiliated with Lawrence Berkeley National Laboratory. The Berkeley Earth Surface Temperature Study combines 1.6 billion temperature reports from 16 pre-existing archives."

 - So this data is gathered from many stations and sources by Berkeley Earth , and this Kaggle dataset is a subset of all of the data from Berkeley Earth , we will be using a cleaned and formatted version from this Kaggle Site , "https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data/data?select=GlobalTemperatures.csv"
and focus on the GlobalLandTemperaturesByCountry file presenting monthly temperatures of countries from 1743 to 2013. 








4. Why does this data set intrigue you? (2 points). 

- This dataset intrigues me as Climate Change is an important topic in our society today and being able to accurately forecast climate can be very beneficial to the earth sciences. In addition we have data at the country level so we will be able to create possibly different time series models by country , continent , or even group by month and average the temperature values to create a time series model to predict global temps
so there is flexibility in the types of models we create . Also data is currently at the month level but we can also group by year and average month results to make a time series model where each time step is a year so using this data will allow us some flexilibility if we want to create models at the yearly , continent, or global level . 
