# Vulnerable-Counties-Python-Covid19-Analysis

### Business Question
Covid-19 has been ravaging communities and pushing hospitals past maximum capcity in areas around the world. Although predicting exactly how strong of an impact Covid-19 may have on a community is difficult, it is important for city governments and public health officials to use data available to mitigate their most vulnerable areas and populations. As we know, older populations and younger populations have a higher risk of complications as a result of COVID-19. Thus, leaders may want to answer the following: Which counties are most vulnerable to a severe outcome from COVID-19 exposure, and do these counties have the medical facilities and hospital resources to adequately deal with the crisis? Moreover, although social distancing should be regulated everywhere, for which communities is this most essential?

### Data Questions
How does our Homeland Infrastructure Foundation Level data on available hospital correlate to our JHU COVD-19 death rate and recovery data? How does our county data, notably on population breakdown, correlate to our JHU COVID-19 data? Is there a strong correlation between these factors or do other external factors lay a heavy hand on the data? How do these data sets come together to gauge county demographics and hospital resources? 

### Data Answers
Our data showed us a number of things, which put together helped paint a better picture of COVID-19. I'll first list out a summary of our data visualizations
1. A bar graph of US counties based on population (going from most to least populous)
2. A bubble graph of US counties with population under 18 and population over 60 on the axis and the size of the bubble corresponding to the amount of hospital beds available in the county
3. A bubble graph with the same axes but bubble size corresponding to # hospital beds per 1000 people
4. A correlation heat map of all of our county data with JHU COVID-19 data

Some data important data driven solutions (and further questions) are the following:
1. Franklin County Washington represents a substantial group of counties with high populations of under 18 year olds, but low numbers of hospital beds. The other side of that spectrum (high poplulation of 60+ and low hospital beds) does not seem to be as common, but counties such as Flager, FL provide the exception.
- How dangerous is this amidst the COVD-19 crisis. Is there information about if neighborhing counties for example, have greater hospital capacities that can support less adapted counties? Could we see create a map based on population- with the age label on one axis, amount of hospital beds in another and the circle area the size of population?
2. Hospital beds per 1000 people has no co
