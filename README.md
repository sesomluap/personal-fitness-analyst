# public-health-data
Project 1

Scope: 
We chose to do a health project but the data we received seemed limited so we decided to source our own data and we wanted to compare poverty rates with various health and environmental health variables. We settled on Arsenic, Heart Attacks, and Cancer rates as this data was the easiest to find from the MN Health's public information page. We pulled poverty data by county and year using the census API. We also obtained heart attack death data from the CDC. 

Data:
The census data was a bit unwieldy if we wanted to include demographic breakdowns such as race, gender, or age. While this was interesting information, much of our health data didn't include these breakdowns so was ultimately less useful than we had originally planned. For the most part, we decided to look at overall poverty rates and also county types where we did see some differences. We used OMB definitions for county types. 

FYI the importing of census data from the API takes about a half hour to run as we ended up pulling in a lot of data. Sorry for that. 

Analysis:
We decided to search and see if poverty rates increased environmental hazards like arsenic or health related illnesses like heart attacks or cancers. We didn't find strong correlations for any of these with poverty. For arsenic this made some sense as the state overall has some of the highest levels. Time constraints kept us from teasing out the data in every possible way, so it's possible that firmer conclusions could be found in our dataset. Regardless, further analysis would be needed on all as we have found other experts reviewing these subjects and finding some correlation. Our lack of results to not mean there is no connection and more research would be needed. 

Limitations:
The specific health conditions may not be the best representatives for the analysis. For instance, cancer deaths might reveal additional insights when compared with poverty. 
Definitions of poverty can differ, as can ways of measuring various stats reviewed. Perhaps heart attack and cancer rates per 100k are less useful with small counties. 
Limiting to MN data may skew the results for a number of reasons. The data set is smaller and some variables are not the same.  
Consulting with expert statisticians may be required when comparing some of these data sets. For instance, we were past our limits with r-squared and p-values on heart attacks and cancer. 

Conclusion
While the initial analysis did not reveal strong correlations, it's important to note that the absence of results does not imply the absence of a connection. Further research, possibly incorporating insights from experts in the field, is recommended for a more comprehensive understanding of the relationships between poverty, environmental factors, and health outcomes.

Sources:
Used code we learned in class. 
Used code from previous in-class activities and homework assignments. 
Used ChatGPT to help write and debug code, it was especially helpful to fix our years column in some MN data that had years lumped together in 3 year bundles compared to our poverty data that was 1 year at a time. 

Additional Sources:
https://stackoverflow.com/questions/39291499/how-to-concatenate-multiple-column-values-into-a-single-column-in-pandas-datafra
https://sparkbyexamples.com/pandas/pandas-concatenate-two-columns/
https://ourcodingclub.github.io/tutorials/pandas-python-intro/
https://realpython.com/pandas-plot-python/
https://neptune.ai/blog/pandas-plot-deep-dive-into-plotting-directly-with-pandas
https://www.youtube.com/watch?v=xi0vhXFPegw&t=2131s
https://stackoverflow.com/questions/32244753/how-to-save-a-seaborn-plot-into-a-file
https://www.statology.org/matplotlib-legend-position/
https://w3schools.com/python/matplotlib_histograms.asp
https://www.w3schools.com/python/matplotlib_pie_charts.asp
https://stackoverflow.com/questions/11346283/renaming-column-names-in-pandas
https://www.geeksforgeeks.org/get-n-largest-values-from-a-particular-column-in-pandas-dataframe/ and https://www.geeksforgeeks.org/get-n-smallest-values-from-a-particular-column-in-pandas-dataframe/


