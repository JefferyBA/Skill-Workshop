# Skill Workshop 
The Tableau Final deliverable work 

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





