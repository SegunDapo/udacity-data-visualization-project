# Ford GoBike System Data Exploration, Explanation and Visualization
## by Oladapo Oluwasegun


## Dataset

> The Ford GoBike System is a public bike sharing system in the San Francisco Bay Area, California also called the Bay Wheels. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States with nearly 500,000 rides since the launch in 2017 and had about 10,000 annual subscribers as of January 2018.

> This data set includes over 180,000 records/information about individual rides made in the bike-sharing system, their monthly individual trip data in February, 2019.


## Summary of Finding

#### Findings in Data Cleaning Process
* Missing values were found and removed as they didn't show any statistical significance
* 	Datetime columns types were modified to datetime type
* 	New columns were created from datetime columns (showing day, day of week, hour) to give more insights. Datetime columns were removed afterwards.
* 	New Column was created to show age and age group instead of birth year and birth year column was removed.
* 	Outliers were checked in age columns and removed due to non-statistical significance.
* 	All unnecessary columns were removed to focus more on the significant data columns.
#### Findings in Data from exploratory visualizations
* Most Users are subscribers, as most of the total trips are for subscribers showing that people will be more likely to engage in the service on consistent basis and subscribe.
* Males represent around 76.2 % of the total trips giving more indication about females not prefering bikes as a go-to for workouts.
* Age range is mostly between 25 & 35 years, giving high indication that youth are more interested in bike trips.
* People use bikes mostly on working days (Monday - Friday) as they use it on regular basis not just for entrtainment.
* Rush hour in bike trips would be between around 8 AM till 6 PM.
* Trips duration is highest at age range from 20 to 40 as expected as they are the most users.



## Key Insights for Presentation

> Different usage pattern/habit between the two type of riders are seen from the exploration. Subscribers use the system heavily on work days i.e. Monday through Friday whereas customers ride a lot on weekends, especially in the afternoon. Many trips concentrated around 8-9am and 17-18pm on work days for subscribers, yet customers tend to use more in the late afternoon around 17pm Monday to Friday. The efficient/short period of usage for subscribers corresponds to their high concentration on rush hours Monday through Friday, indicating the use is primarily for work commute. The more relaxing and flexible pattern of customer use shows that they're taking advantage of the bike sharing system quite differently from the subscribers, heavily over weekends and in the afternoon, for city tour or leisure purpose probably.

> In the exploration, I found that there are two types of user:
1.	Subscriber
2.	Customer

> I realised the subscriber users have the highset number of trips at 8.AM and 5.PM and that because the work hours (start and end work). Also the rides trips between 12.AM and 5.AM has the lowest number of rides and that it's hours sleep. And on the week day I found the weekday have more trpis per day than weekend day. Unlike customer users. The customer users the number of trips are start growing from 7.AM to 5.PM (highset) then it's will be decreased. Also they have the highset trips on weekend. Also I found most ages are between 21 to 40 years old for both subscriber users and the customer users.# udacity-data-visualization-project
