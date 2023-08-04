# cyclistic-case-study
Case Study 1 Project 

Ask 

In this project, our stakeholders, Cyclistic, want to convert our casual members into annual members. Cyclistic is a company that specializes in renting out bikes in Chicago. They have various stations to rent and park in the city.    Casual members are considered by those who purchase a ride for a one-time trip, or a full day. Annual members are considered by those who purchase a membership annually. 

	The questions that are being asked are, how do annual members and casual riders use Cyclstic bikes differently? Why would casual riders buy the annual memberships? How can Cyclistic use digital media to influence casual riders to become members? 


Prepare 

	We will be using a dataset based on Kaggle. The dataset includes a ride id, and rideable type, as there are bikes that support handicapped riders as well. The data also includes at start point address and id. With also an endpoint address and id. Finally, we conclude this dataset with the status of each other whether they are casual or an annual member. 

Process 

	For this dataset, I started with data cleaning by sorting casual and annual members apart. I have also calculated the difference between the start time and the end time of each ride, finding the average time of each ride, and adding it into a column name “ride_length.” I followed it up by calculating and creating a column “day_of_week”. This helps us determine which day of the week the rider uses Cyclistic services. For example, 1 would be the equivalent of Sunday, and 7 would be Saturday. 












Analyze 

During the analysis phase, I made calculations on the average and the max of all of the ride lengths. In addition to the mode of the day of the week. The results conclude that the average ride length time was 0:35:51. Most riders would average barely past 30 mins in each other. With the exception of the rider who clocked in the most hours for one service. Which was 978:40:02. This result was purchased by a casual rider, and they would not be the last person who clocked in more than 100+ hours. Finally, I have calculated the mode of the days of the week each rider bikes. In return, the result was 1. This means most riders, casual or annual, would ride on a Sunday. 


	
AVERAGE of ride_length
day_of_week












member_casual
1
2
72:00:00
4
5
6
7
casual
0:58:53
1:02:19
1:24:26
1:03:14
1:14:54
1:50:33
1:12:40
member
0:26:44
0:17:48
0:21:43
0:16:19
0:20:00
0:18:23
0:25:55



We analyze the average ride length of each day. What was the return in the dataset? We analyzed that casual riders tend to ride for a long period of time compare to annual riders. Annual riders' average time may be lower because they tend to use Cyclistic service to commute around the city or usually to work and back home. As casual riders, they tend occasionally ride for a long period of time for one ride or a full day. 




casual
member
AVERAGE of ride_length
1:13:04
0:21:28


	We have also analyzed the average ride time between a casual member and an annual member. This concludes that casual riders use Cyclistic for a long period of time compared to an annual member. As I stated earlier, this result is leading annual members using Cyclistic to commute regularly to work or their preferred destination and back home. 

Finally, we conclude this analysis by calculating the count number of trips of a casual and annual rider on each day. We have a higher number of annual riders each day. The challenge I believe now is looking into the casual members and seeing who could potentially become an annual member. 

Share 

Going back to the analysis from earlier. We can determine that the difference a casual member and an annual member is the difference in the length of ride each type of member use. Casual members use Cyclistic on average for almost over an hour each day with an anomaly of 100+ from time to time. As annual riders use services for an average of under 30 minutes each day. The count for each annual and casual rider differs by double for annual riders. They are expected to use the services more since they have unlimited access after purchasing an annual membership. The reason why casual riders would want to purchase an annual membership is if they feel like they are purchasing a one-time ride or a full day multiple times. I believe these are the casual members we have the best chance to convert to annual members. Specifically the ones in the dataset who logged in over 100 hours. Are they taking advantage of the system? Are they trying to find a loophole to save as much money as possible? Maybe we need to possibly have a change in strategy. Cyclists could use digital media to communicate with casual riders to find out which packages work best for them. Especially if they are using our services more than once a week. 

Act 

In conclusion, the best way to convert casual into annual riders is we need to find casual riders who purchase a ride more than once a week. Communicate them through media to find the best way for those members to switch to an annual membership. That way both parties can be satisfied with their purchases. As we understand the difference between casual and annual riders through the average length of time through rides throughout the week. 
