### Bikesharing from NYC to gauge Bikesharing info for Des Moines. 

# Overview
  The purpose of this analysis is to use data from New Yorks widely successful CitiBike sharing program and seeing what can be used from it to implement a similar 
  system for Des Moines Iowa. To do this, we used Tableau to create visualizations of the data. [Tableau Dashboard](https://public.tableau.com/app/profile/tessa.c5417/viz/Citibike_16238082679230/PreliminarylookintoBikesharingdata)

 #   Results:
 ![Checkdisout](https://github.com/TCJester10/Bikesharing/blob/main/Images/Checkouts.png)
 
 This is the first visualization to discuss. This shows that by far most rides are short, peaking at 5 minutes, and never really going more than an hour. There are trace 
 few beyond an hour, and it is likely that those bikes were just left behind and never turned in. 
 
 ![Checkoutthesegenders](https://github.com/TCJester10/Bikesharing/blob/main/Images/Checkout%20by%20Gender.png)
 
This is the same visualization, but with a filter for gender. As seen, males use the system far more than Females or those who did not specify their gender, and the 
pattern for usage is the same across all three categorizations. 

![Whenbikes](https://github.com/TCJester10/Bikesharing/blob/main/Images/When%20used%20and%20gender.png)

These two visualizations show that the work commute is by far the biggest driver of usage, as darker shading means more usage. This suggests that working people use this
system more than those who are justchecking it out for fun. I think it is interesting that while the pattern for usage is consistent with men and women, those who marked
gender as unknown rode more on the weekends. I believe this could be that those who marked unknown were likely just trying the system out for fun and did not care to
give their data accurately. 
(will go more into this later)

![Wherebegin](https://github.com/TCJester10/Bikesharing/blob/main/Images/Start%20Locales.png)
![Whereend](https://github.com/TCJester10/Bikesharing/blob/main/Images/End%20Locales.png)

These two maps show where the bikes started and ended. Red and green are where bikes started, with Green being more bikes, while gold and purple are where bikes ended,
with purple being more bikes. It is interesting to note that while no bikes started in New Jersey across the river, several ended there. As can be seen, most rides never 
leave lower Manhattan, where work and population centers are densest. This is good evidence that bike stations would be best located where people work and live, striving
to keep stations five minutes apart at most. 

![subs vs customers gen](https://github.com/TCJester10/Bikesharing/blob/main/Images/Subs%20vs%20Cus.png)

This visualization backs up previous ones by showing two peices of information. The days most used by subscribers to the system, and the the days most used by each
gender categorization. What this shows is that in those marked male and female, there are by far more people using the bikes on workdays, though weekends aren't 
sparse for male subscribers. This also shows that subscribers are also much more likely to use the system multiple times, which would be the best way to ensure long
term success of a system. While those who marked unknown are more likely to be customers and use the bikes more on weekends. I believe that one explanation for
this is that those who marked their gender as unknown likely just filled out whatever was easiest on the data handover, as they are more likely to be just trying the
system out for fun or novelty.

# Summary
All in all, for Des Moines to have a succesful bikesharing program, it would be important to seek out subscribers. Instead of trying to target it to out of towners
try marketing it to working professionals, as New Yorks system is primarly used by working people who subscribe to the system. It would also be important to make sure
stations are no more than a five minute ride away from each other, as most rides on the CitiBike system are short and where most people live and work. It will be 
tougher for Des Moines to mimic this, as it is more spread out and decentralized than New York is. I would advise two more visualizations for this dataset to show
that working subscribers are the primary users. One would be an age breakdown by day of the week, and the other would be an age and subscription breakdown.
If we see that most people who ride on workdays are from 20-50, we could conclude that the working population is the primary users. And if we see that most subscribers fit that age breakdown, we could see that most returning customers are working adults. 
