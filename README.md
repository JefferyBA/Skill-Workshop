# Skill Workshop 
The Tableau Final deliverable work 


link to site:https://jefferyba.github.io/Skill-Workshop/

....
https://public.tableau.com/profile/jordan.fischer4857#!/vizhome/DCBikeshareAnalysisBASkillsgroup8/BikeshareStory?publish=yes
### Progress report 2 – Business Analytics Skills Workshop, Group 8

Jordan Fischer
Austin Frazer
Tingyu Xie
Jingbo Zhang
Junfei Zheng

##### As we work our way through the Tableau tutorials, we have some basic findings on the data…

##### We can get an idea of most popular stations: 

We can get an idea of most popular stations: 

![picture1](https://user-images.githubusercontent.com/21350380/32204532-2ff21156-bdc0-11e7-928c-944ed24ded7a.png)

…we noted that the **top 5 stations for departure and arrival are the same, but in the next 5 there is more variation**. It makes sense that the bikes near Union Station (the city’s bus and train station) would be most popular, as people ride the bikes to or from their houses to this central travel hub. 

We can also see the clear **influence of rush-hour** on bike use:

![picture2](https://user-images.githubusercontent.com/21350380/32204536-34448aea-bdc0-11e7-9769-3778d848b190.png)

…where **Sunday and Saturday have a bell-shaped distribution**, but **Monday-Friday have bimodal distributions with peaks at 8am and 5pm (start times).** 

We can also get a picture of the most popular days of the week for riding. In contrast to our assumption that it would be Saturday or Sunday, in fact we found that the most popular day for riding was **Wednesday (followed very closely by Tuesday)**:
![picture3](https://user-images.githubusercontent.com/21350380/32204538-36036734-bdc0-11e7-96d7-31754978db97.png)

However, we did find a predictable pattern regarding weekends: trips made by registered members, who likely use their membership to commute to and from work, dropped off during weekend days, but trips made by casual members, who take **one-time trips or single day passes, increased during the weekends.** 

![picture4](https://user-images.githubusercontent.com/21350380/32204539-379b5778-bdc0-11e7-9744-92f12f4b678f.png)

We also thought the cooling climate in DC from October to December might be a factor. Overall, this seasonality is indeed factor, as can be seen in the **decreasing rates of use over November and December:** 

![picture5](https://user-images.githubusercontent.com/21350380/32204540-39be1ee6-bdc0-11e7-9a7a-6d32cbc19633.png)

Furthermore, day-to-day weather patterns during this period further influenced usage patterns. We were pleased to find that bike share use followed the weather very closely, with **higher temperatures resulting in more trips and precipitation resulting in fewer trips.** Note especially the effect of storms on 10/1, 10/8-9, 10/22, 11/9, 12/6,12/17, and 12/24. The low number of rides December 24-26 is also likely a factor of the widely celebrated holiday, Christmas:

![picture6](https://user-images.githubusercontent.com/21350380/32204542-3ccca1ca-bdc0-11e7-81fd-d55a0962fe50.png)

We are even making progress with our geographical analysis, with a first attempt at a path map for trips taken around DC:
![picture7](https://user-images.githubusercontent.com/21350380/32204546-3fa7a4c6-bdc0-11e7-9c8b-b16d104439f1.png)

As we continue to work on this, we will need to find ways to highlight certain pieces of the data, and cut down on the noise in order to identify geographical patterns. 

Going forward, we hope to work with geographical coding variables like ‘neighborhood’, but are unsure of the practicality of that, whether it would be better to code it in Excel, or to use the grouping function in Tableau. We also hope to look at trip length – this bikeshare company charges extra to users who keep bikes longer than 30 minutes, so why would a user keep a bike for more than 30 minutes? Our hypothesis is that this will be the result of long trips with few stations in between the departure and arrival points, such as from the suburbs to the city center, or vice versa. We also hope to work with the variable of member type, including comparing station use by ratio of member type, our hypothesis being that stations in more residential and business districts will be used by more registered members, while stations on the National Mall and near museums will be used by more unregistered members. 


To make the path map clearer, we create a geo-filter dividing the paths into four group, NW(northwest), SW(southwest), NE(northeast), and SE(southeast) based on the stations’ latitudes and longitudes; for instance, if the station’s latitude and longitude, are larger than the medians of all stations’ latitudes and longitudes, respectively, the station is regarded as one locating in the NE. Then we obtain the following four sub-maps:

![picture1](https://user-images.githubusercontent.com/21350380/33451864-5529dd24-d5de-11e7-8cdb-f47468509747.png)
![picture2](https://user-images.githubusercontent.com/21350380/33451870-59d763aa-d5de-11e7-8e00-31aafaeace88.png)
![picture3](https://user-images.githubusercontent.com/21350380/33451871-5ab34fa0-d5de-11e7-9a29-c632b2c431d8.png)
![picture4](https://user-images.githubusercontent.com/21350380/33451873-5b90dbb8-d5de-11e7-90fd-7a7d2022ec71.png)

Due to huge quantity of the data, even if we split the map into four, they are still too complicated to make some conclusions in details, although we can clearly see that the density of path in NW region is much less than that in other three regions, and the travel distances there are longer than those in other regions. 

Next, we looked at some basic demographic data around bike use: 
![picture5](https://user-images.githubusercontent.com/21350380/33451874-5d497abe-d5de-11e7-9455-33989f3f35bc.png)

From the Bike Usage and the Age relationship we can see that most of the bikes are used in the younger age area. Bikes are primarily used in areas where the median age is between 0 and 37.7 years. 

Next we looked at the average time residents have been residing there. 
![picture6](https://user-images.githubusercontent.com/21350380/33451877-5e1dab68-d5de-11e7-9a59-2be20624659e.png)

The bike usage and the length of the residence relationship indicates that shorter-time residents are more likely to use the bikeshare bikes. This makes sense, as long-time residents will be more likely to invest in buying a bike of their own, but a short-term resident will not want to go through the hassle of buying the bike and having to re-sell it after just a short time. There are more biker users in the light color area, where residents have lived on average 0 to 10.7 years.  

Finally, we looked at membership type most commonly used at stations around the city. As hypothesized, the casual members were much more common at stations downtown and especially in the National Mall, a location that caters specifically to tourists and visitors, and has comparatively little to offer full-time residents. 
![picture7](https://user-images.githubusercontent.com/21350380/33451878-5f740746-d5de-11e7-9966-0bf1ad06cc6d.png)
![picture8](https://user-images.githubusercontent.com/21350380/33451884-61ceb540-d5de-11e7-913d-93be11c2941d.png)
![picture9](https://user-images.githubusercontent.com/21350380/33451888-62c623f2-d5de-11e7-88ce-2a4f7b254de7.png)

We create a new calculation ‘pair’ to represent the ride route. We can see that these routes with highest number of records are either mostly taken by casual or registered riders. Those routes mainly taken by casual riders represent some typical travel routes while those taken by registered riders represent some typical commuting routes. Then we separate the routes into two subgroups: one that have the same start station and end station and the other that have different start station and end station.

![picture10](https://user-images.githubusercontent.com/21350380/33451890-63a5bf26-d5de-11e7-9320-a556271487a5.png)
![picture11](https://user-images.githubusercontent.com/21350380/33451891-64ca1bb8-d5de-11e7-85c1-3e39fbd28ea6.png)
![picture12](https://user-images.githubusercontent.com/21350380/33451892-659a0a4e-d5de-11e7-9e0b-078893448669.png)
![picture13](https://user-images.githubusercontent.com/21350380/33451893-666d944a-d5de-11e7-8821-c10f1f69ecb7.png)





