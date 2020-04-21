# Vulnerable-Counties-Python-Covid19-Analysis

### Business Question
COVID-19 has been ravaging communities and pushing hospitals past maximum capcity around the world. Although predicting exactly how strong of an impact COVID-19 may have on a community is difficult, it is important for city governments and public health officials to use available data to mitigate their most vulnerable areas and populations. As we know, older populations and younger populations have a higher risk of complications as a result of COVID-19. Thus, leaders may want to answer the following: Which counties are most vulnerable to a severe outcome from COVID-19 exposure, and do these counties have the medical facilities and hospital resources to adequately deal with the crisis? Moreover, although social distancing should be regulated everywhere, for which communities is this most essential?

### Data Questions
How does our Homeland Infrastructure Foundation Level data on available hospital correlate to our JHU COVD-19 death rate and recovery data? How does our county data, notably on population breakdown, correlate to our JHU COVID-19 data? Is there a strong correlation between these factors or do other external factors lay a heavy hand on the data? How do these data sets come together to gauge county demographics and hospital resources? 

### Data Answers
Our data showed us a number of things, which put together helped paint a better picture of COVID-19. I'll first list out a summary of our data visualizations:
1. A bar graph of US counties based on population (going from most to least populous)
2. A bubble graph of US counties with population under 18 and population over 60 on the axes and the size of the bubble corresponding to the amount of hospital beds available in the county
3. A bubble graph with the same axes but bubble size corresponding to # hospital beds per 1000 people
4. A correlation heat map of all of our county data with JHU COVID-19 data

Here are some data important data driven solutions (and further questions):
1. Franklin County Washington represents a substantial group of counties with high populations of under 18 year olds, but low numbers of hospital beds. The other side of that spectrum (high poplulation of 60+ and low hospital beds) does not seem to be as common, but counties such as Flager, FL provide the exception.
- How dangerous is this amidst the COVD-19 crisis? Is there information on whether neighborhing counties for example, have greater hospital capacities that can support less adapted counties? Could we see create a map based on population- with the age label on one axis, amount of hospital beds in another and the circle area the size of population?
2. Hospital beds per 1000 people unexpectedly has no correlation to deaths and number of cases. This causes us to reevaluate the idea of of number of hospitals and bed as being a marker of how hardly hit communities may be. 
- Analyzing a correlation with different sets such as average country economic income, proximity to airports or numbers of people with high risk factors or pre-existing conditions (perhaps due to community pollution or heavy smoking) could perhaps give a better correlation. This in turn can help paint a more accurate picture of factors that may heavily aggravate COVID-19 spread. 
3. Some factors do somewhat stand out from the data as being correlated. For example, there is a much stronger positive correlation between the number of males and females over age sixty and the death rates. This positive correlation also occurs between death rates and number of males and females under age 18. Both of these positive correlations are also consistent with the number of cases present in a county.
4. Intrestingly, there is also a positive correlation between hospital bed counts and these populatiions. This means that despite having the most medical facilities, the death rates are still highest amongst these age groups (which also helps explain the lack of relation between hospital beds and cases/deaths) This would encourage us to find more data as to what exactly can protect these populations, who are dying despite having the most medical care available. If this data was aggregated by people who have medical insurance, or my economic income, would the data be broken down in a different manner?

### Business Answer
To conclude, what we can determine with certainty is that counties with heavy populations of people aged 60+ years or under 18, should be most cautious about the pandemic spread, somewhat regardless of the availability of hospital beds. Moreover, though, it seems a large number of outside factors are at play in counties that have many hospitals that stop this metric from being effective. Governments and policy makers should look into why that is. 
