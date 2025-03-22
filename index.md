---
layout: default
---

* * *

## Data introduction
The dataset that provides the basis for this analysis is a concatenation of a historical [dataset](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry/about_data) of crime incidents recorded in San Francisco in the time period 2003-2018
and a corresponding [dataset](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present/wg3w-h783/about_data)
with ongoing data collection in the time period 2018-2025. It should be noted that for the
purpose of fair comparisons between whole years, we exclude data from 2025 from this analysis.
The dataset consists of 2342093 unique crime incidents with a number of interesting recorded
features including, but not limited to: unique incident number, crime category, date and time
of the incident report, geo location and district.

## History of drug related crimes in SF

San Francisco has a long track record of struggle against drug crime. Historically, 
abuse of pain killers such as OxyContin has been a big problem in SF, both as a cause 
for addiction in itself, but also as a path towards even more hardcore drugs, such as 
heroin. In 2017, a study showed that 80% of heroin users reported beginning with 
prescription opiods [[1]](https://www.sfpublicpress.org/san-franciscos-fatal-overdose-crisis-was-decades-in-the-making/).
In recent years, the use of fentanyl as seen a huge increase, especially among the homeless 
population of SF. Figure 1 shows the change in the number of drug related crime incidents 
throughout the years [[2]](https://www.ucsf.edu/news/2024/05/427651/smoking-fentanyl-rising-sf-deadly-new-risk-overdose#:~:text=San%20Francisco%20reached%20an%20all,cocaine%2C%20are%20on%20the%20rise.).


![Fig1](assets/images/Drug_crimes_by_year.png)
> Figure 1: The plot shows a significant decrease in the overall number of drug related crime incidents
> since the 2000s. One can observe first a steep decrease followed by a steady decrease until crime incidents
> hit its lowest level in the pandemic time period. Since 2022 there has been a resurgence in crime incidents.


## Drug related crime trends by district

As with many other types of crime, drug related crime does not usually distribute evenly over large cities.
In general, there exist certain indicators that typically go hand in hand with large amounts of drug activity.
These are things such as poverty level and homelessness. Tenderloin is the district of SF with the highest 
level of homelessness and is in general known for its prevalence of social issues [[3]](https://en.wikipedia.org/wiki/Tenderloin,_San_Francisco).
In figure 2, we illustrate the distribution of drug related crime throughout SF.


<html>
<head>
</head>
<body>
    <iframe src="plotly_plot.html" width="1000" height="510"></iframe>
    </body>
</html>
> Figure 2: The plot shows the distribution of drug related crime in all districts of SF in the time period 2003-2024.
> It is clear from the plot that Tenderloin is by far the most significantly impacted district with Southern and Mission
> also showing relatively high levels of drug related crime. On the other hand, we have Richmond and Taraval in the
> western-most parts of SF where drug crime is largely insignificant compared to the aforementioned districts.


<html>
<head>
</head>
<body>
    <h1>yoot bokeh plot</h1>
        <p>(click the categories)</p>
    <iframe src="bk_plot.html" width="1000" height="510"></iframe>
    </body>
</html>
