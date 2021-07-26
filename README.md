# Bikesharing

## Overview 
The point of this project was to use bikesharing data from NYC to provide investors with some insight as they try to establish a bikesharing presence in Des Moines. The data that was used was from August 2019. In order to convey the information to the investors, Tableau was used to created different charts. Before creating the various charts in Tableau, the *tripduration* column was converted from an integer to a datetime datatype using Python. 

A link to the Tableau story can be found here: [link to story](https://public.tableau.com/app/profile/naomi.shields/viz/NYC_Citibike_Challenge/Story1)

## Results 

### Customers
To kick things off, A pie chart that breaks down the rentals by user type was created.
![Customers](https://github.com/naomishields/bikesharing/blob/main/Story/Customers.png)
This chart shows that the majority of customers during this time were subscribers.

### Gender Breakdown 
Next, a pie chart was used to break down the gender of the customers.
![Gender Breakdown](https://github.com/naomishields/bikesharing/blob/main/Story/Gender%20Breakdown.png)
It can be seen that males had the highest percentage of rentals. Then females had the second highest percentage followed by customers with an unknown gender.

### Checkout Times for Users
Then, a line graph was created to visualize the checkout times for all the users.
![Checkout Times](https://github.com/naomishields/bikesharing/blob/main/Story/Checkout%20Time%20for%20All.png)
It can be seen that most bikes were returned around ten minutes after their start time. 

### Checkout Times by Gender
A line graph was also created to look at checkout times broken down by gender.
![Checkout Times by Gender](https://github.com/naomishields/bikesharing/blob/main/Story/Checkout%20Time%20by%20Gender.png)
This graph shows that both males and females tended to return their bikes before the 20 minute mark. However, those with an unkown gender seemed to turn their bikes in anywhere from 10 - 30 minutes after their start time. 

### Trips by Weekday 
A heatmap was created to look at the trips by weekday per hour. 
![Trips by Weekday](https://github.com/naomishields/bikesharing/blob/main/Story/Trips%20by%20Weekday.png)
This heatmap indicates that their are several times throughout the week when bike rentals are most popular:
* Monday from 5pm to 6pm 
* Tuesday from 5pm to 6pm 
* Thursday at 8am 
* Thursday from 5pm to 6pm

It also shows that they are least popular in the mornings before 6 am

### Trips by Gender
A heatmap was also created to look at the trips by weekday per hour broken down by gender.
![Trips by Gender](https://github.com/naomishields/bikesharing/blob/main/Story/Trips%20by%20Weekday%20by%20Gender.png)
This graph continues to show that males had the highest number of bike rentals. It also shows that popular times do not vary much by gender. 

### User Trips by Weekday 
Finally, a heatmap was created to look at trips by weekday per hour broken down by gender and user type. 
![User Trips by Weekday](https://github.com/naomishields/bikesharing/blob/main/Story/User%20Trips%20by%20Weekday.png)
This heatmap shows a few things:
* Most users of unknown genders were just customers and not subscribers
* Most male and female users were subscribers
* The most popular days of the week for rentals were Thursday and Friday

## Summary 
Based on the visualizations, some valuable insights were attained. It can be concluded that most of the bike rentals in NYC during August were completed by male subscribers. It can also be concluded that the most popular day for rentals was Thursday at 8 am or from 5-6pm. Also, most of the rentals were short-term and the trips were completed within 20 minutes. 

For further analysis two additional visualizations could be added:
* A heatmap of trips by weekday per hour broken down by age. This could provide insights on age groups that use the bikes the most.
* A map of start station with a color marker for user type. This could potentially show differences between locals and tourists. I would think more subscribers would be locals and they would use the bikes in areas that are not as common tourist hotspots. Whereas, more tourists would just be customers. 




