# Descriptive Insights Translation Project 
#### Author: Yinhui(Kami) Yang

## Introduction

SafeGraph is a company that works with cell phone location data. People have ever pressed “Accept Terms & Conditions” in certain apps, it is
very likely that people have sent an anonymous ping of their location to a location-data-services who then sells people’s information to
companies like SafeGraph.

Regarding this project, we will analyze three datasets (Datasets: king_originvisits.Rdata, king_dailyvisits.Rdata, neighborhood_names) that reflect
data from July 2020 in the King County neighborhood area around Seattle. More specifically, we will look at daily visits to analyze people’s trends
at different companies. Based on the dataset’s timeframe, it is striking to see there is a correlation between people’s daily visits and impact of the
Covid-19 pandemic.

## Where are the neighborhood near by Seattle people visits the most?
<img width="551" alt="WX20220222-141245@2x" src="https://user-images.githubusercontent.com/81647911/155229372-1d5ab2b8-50e0-4329-b798-6de2bdd067b1.png">

The most popular districts, as we can see, are the Northeasts, Northwests, and Southwests. Based on this data, we may conclude that throughout the summer, individuals prefer to visit lively areas in Seattle's Northeast and Northwest. Since the COVID-19, most places were still closed throughout the summer, and there was a lot of protesting action in the Downtown, Central, and Delridge neighborhoods during the COVID-19 period. This can be explained by the fact that traffic in these communities was substantially lower.

## Where are they tend to visiting the most?

The Northeast, Northwest, and Southwest are currently known to be the most popular districts. Let's take a closer look at the data and see where they like to go.

Note about the data: I am unable to entirely extend the name due to the Naics Title which includes industries names being too long, but we can still extract the kind of industries serviced.

<img width="900" alt="WX20220222-141319@2x" src="https://user-images.githubusercontent.com/81647911/155229000-99b209af-e766-4552-966f-759dd0df256c.png">
Full-Service Restaurants and Lessors of Nonresidential Buildings are the top two most frequented sites (except Miniwarehouses).

## Based on these industries, which company do people visit the most?
<img width="898" alt="WX20220222-141333@2x" src="https://user-images.githubusercontent.com/81647911/155229632-7f1b0935-bf65-41f6-aa53-f33604e66018.png">
At Ross Stores, we can observe that the Top 1 Company averages 221.4 visits each day. The majority of retailers have closed after COVID-19, although Ross Stores are considered important stores that remain open during the COVID-19 era. Kohl's is the second most visited firm, owing to the closure of the fitness facility, and individuals constructing home gyms. Coastal Farm and Ranch, Sears Home Services, and Macy's are among the companies that follow.

## Where do people go besides their basic needs?
<img width="697" alt="WX20220222-141356@2x" src="https://user-images.githubusercontent.com/81647911/155229806-6b5a16e4-ce0e-4285-aec3-74092b9352f1.png">

According to the beginning of the project, I am analyzing three datasets that reflect data based on people's daily visits, as stated at the start of the research. Apart from people's fundamental necessities, I've merged two datasets to acquire the daily visits to get the Top 5 firms. Then there's the most fascinating phenomenon: Starbucks and UW Medicine daily visits both skyrocket at the same time. They receive much more daily visits than the other three firms.

## Driving a closer look at the average daily visits between UW Medicine and Starbucks

The orange line indicates UW Medicine's activity, and the daily visitors are moving up and down with a broad range.
Starbucks' operations are shown by the blue line, and daily visits fluctuate within a short range. This behavior is most likely linked to people's everyday coffee consumption.

<img width="888" alt="WX20220222-150556@2x" src="https://user-images.githubusercontent.com/81647911/155234716-6782b9a4-eb50-4f8f-acdd-7d49cccb34bb.png">

## Conclusion
Finally, during the COVID-19 time, King County inhabitants reduced their daily life trips foot traffic throughout the month of July, 2020. The average visits in the Northeasts, Northwests, and Southwest regions are roughly 26,593 visits. We also note the Top 10 industries firms in King County, as well as the Top 10 companies with the most average visits in the people-based requirements category. We can clearly see the evolution of people's life patterns based on the examination of the aforesaid data.
