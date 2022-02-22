# BUAN 4220 21SQ - Data Translation Project
Author: Yinhui(Kami) Yang

#### Introduction

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
