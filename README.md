# USA-Air-Quality-Improvement


Business Understanding
In this project, we are working in the analytics team for the United States Environmental Protection Agency (EPA). The data includes information about more than 200 sites, identified by state, county, city, and local site names. One of the main goals is to determine which regions need support to make air quality improvements. Given that carbon monoxide is a major air pollutant, we will investigate data from the Air Quality Index (AQI) with respect to carbon monoxide. 


Data Understanding
This project uses a dataset called epa_air_quality.csv. It contains 260 rows and 8 columns including date sampled, state name, and Air Quality Index which is a way of measuring the quality of air in a particular area.


Modeling and Evaluation
Employing the concepts of sampling, and central limit theorem, we generated about 10,000 samples. The purpose of this was because we wanted to cover up the lapses of insufficient data, and make the sample mean close to the actual population mean. We also built confidence intervals using a 95% confidence level to give stakeholders specific values for the air quality of major district with low air quality.


Conclusion
The analytical methods resulted in valuable outcomes. The confidence interval at the 95% level of confidence for California's AQI was calculated as [10.36, 13.88], indicating a 95% confidence that the population mean AQI falls within this range. This information can help identify regions that require environmental support to improve air quality, with higher confidence levels indicating more spread out confidence intervals. 
