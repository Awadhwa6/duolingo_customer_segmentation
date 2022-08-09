# Duolingo_customer_segmentation

AIM
Use Duolingo’s user survey data to:
1.	Use quantitative methods to identify a set of user segments/personas
2.	Identify any actionable product or marketing insights

DATA
For my analysis I used: 
1.	Data from Duolingo’s user survey (survey_data.csv)
2.	Usage data from Duolingo for users included in the survey (survey_users_app_usage.csv)

SETTING UP THE DATA
I began my exploratory data analysis by joining these two tables on ‘user_id’ to get my final table. 

DATA CLEANING
1.	I removed the values if ‘user_id’ was missing.
2.	I chose only the data where the number of seconds spent on the survey was more than 5 seconds to remove any casual responses by the users.

DATA MODELING
I used k-means clustering method to identify three primary segmentations of users:
1.	CLUSTER A : Highly motivated users who are active, complete their daily goals and complete more courses.  
2.	CLUSTER B : Less motivated users who are less active, have inconsistency in meeting their daily goals, and have done less courses.  
3.	CLUSTER C : Slow but steady users who are less active on a daily basis, but still complete more courses than average.

RECOMMENDATION
For these three clusters my recommendations are as follows:
1.	CLUSTER A : For highly motivated users, we should make more extensive/advanced coaching courses, as they are likely to set higher goals for themselves and be consistent
2.	CLUSTER B : For less motivated users, we should make smaller courses which can end in a few weeks, instead of month-long courses, which will help to increase their number of completed courses.
3.	CLUSTER C : For the slow but steady users, who do more work in less days, we can design accelerated courses which cover the same content as in a regular course, but spanned out over a smaller period of time than the regular course.



Morevor, I also did a few additional analysis:
1.	Analysis #1 - ANALYSIS ON USERS WITH SUBSCRIPTION
i) Salary-
•	Users with subscription who have higher salaries are more likely to be active on the platform (~74 days)  than those with lower salaries (~63-66 days)

ii) Age-
•	Users under 18, mostly don't purchase the subscription (only 30 users under 18 have subscriptions). This makes sense as they are most likely minors who yet don't earn money.  
•	The younger age categories (Under 18 and 18-34) who purchase a subscription, seem to be less active on average (around ~59 days) than the older age categories (35 +) who seem to be active for around ~75 days on average.

RECOMMENDATION:
•	We should target users with high salaries for subscription related promotions.
•	We should target adults for subscriptions rather than minors, as they have an earning as well as are more active on the platform after purchasing the subscription.


2.	Analysis #2 - ANALYSIS ON LEVEL OF PROFICIENCY vs USAGE
Users with a beginner level of proficiency in the primary language are less active on Duolingo and advanced users are more active.

RECOMMENDATION:
Beginners should be given smaller courses and advanced people can have courses that are more extensive and time-consuming.


3.	Analysis #3 -  ANALYSIS ON OTHER RESOURCES USED BY USERS
We see that users primarily use movies/TV shows as other resources to learn.

RECOMMENDATION:
Making video learning content can be a good strategy to attract users. Bringing in movie/TV industry ambassadors to promote Duolingo can also be useful.


4.	Analysis #4 - ANALYSIS ON INCOMPLETE COURSES
We clearly see that on average, younger users are likely to complete their courses, whereas older people have more incomplete courses

RECOMMENDATION:
Understand why older people don’t complete courses. There can be many reasons: they find the course long and can’t keep up with their daily responsibilities, they are just exploring courses/interests and don’t necessarily want to finish them. For this we can have ‘interest courses’, which don’t cover the course content in depth, but helps you gain an overall understanding.


5.	Analysis #5- ANALYSIS ON CUSTOMER RETENTION AND PROMOTION
Even users who don’t purchase a subscription want to be contacted in the future to learn about more ways to engage with Duolingo.

RECOMMENDATION:
We should have other strategies over and above subscription to gauge user loyalty, as there might be cheaper investments that they would be willing to continue with on Duolingo’s platform.

![image](https://user-images.githubusercontent.com/59432352/183776036-53585d91-623c-423c-b130-23eb4859f520.png)
