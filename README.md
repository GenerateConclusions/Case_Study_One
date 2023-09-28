# Case_Study_One

**CASE STUDY SCENARIO:**

You are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, your team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, your team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve your recommendations, so they must be backed up with compelling data insights and professional data visualizations. 

**PRIMARY STAKEHOLDER:**

Cyclistic’s Executive team 

**ASK:**

How do annual members and casual riders use Cyclistic bikes differently? 

**GOAL:**

Design marketing strategies aimed at converting casual riders into annual members. In order to do that, however, the marketing analyst team needs to better understand how annual members and casual riders differ, why casual riders would buy a membership, and how digital media could affect their marketing tactics. Moreno and her team are interested in analyzing the Cyclistic historical bike trip data to identify trends. 

**BUSINESS TASK:**

Figure out the main differences between casual riders and members to incentivize casual riders to become members.

**DATA SOURCES:**

1. 202203-divvy-tripdata-C
2. 202204-divvy-tripdata-C
3. 202205-divvy-tripdata-C
4. 202206-divvy-tripdata-C
5. 202209-divvy-tripdata-C
6. 202301-divvy-tripdata-C
7. 202302-divvy-tripdata-C
8. 202303-divvy-tripdata-C
9. 202304-divvy-tripdata-C
10. 202305-divvy-tripdata-C 

Cyclistic’s quarter trip data will be the sources used in this analysis to answer the business task.

**PREPARE:**

The data sources are reliable, Original, Comprehensive, Current, and cited making the data sources unbiased and perfect for this analysis. 
The data is made public allowing for use in this analysis.

**Limitations:**

The data is public so recurring casual riders and members cannot be identified due to maintaining privacy along with personal information.

Through the query, we notice that the classic bike is the bike of choice for both members and casuals. One thing to note is there are 5,824 bicycles offered. I would like to know the ratio of each bike offered.

**PROCESS:**

I decided to use Excel for the data cleaning and SQL for the analysis. 
I used Excel because all the data sources are Excel files and it houses all the necessary tools for data cleaning. It also provides pivot tables and pivot graphs allowing for a preliminary analysis before I move to SQL. 

**DATA CLEANING:**

I downloaded and unzipped all the files renaming each to a more standard name so the files can be easily searched when needed in the future. Went to the Data tab in Excel started a query in the table and removed all errors and blanks in each of the columns. I made sure that all of the columns followed the proper formatting. 

**ANALYSIS:**

I created a table that returned all the data I needed for the initial analysis. Combing through the data by querying up the row count and distinct value. I then queried the user count for each day and compared the difference between members and casuals. Noticing that casuals ride more during the weekends while members ride more during the week. I delved deeper by finding the max value between members and casuals on each day of the week noticing that casuals ride more than the members. 

**RECOMMENDATIONS:**

1. Since members ride more on the weekends, we can offer a weekend deal to members. Such as a discounted rate.
2. Casual riders tend to ride more than members so we can offer a membership app that tracks member’s rides and allows them to easily post them in the app or on social media. This will motivate members and potential members. 
3. Bring a friend at a discounted rate or for every minute or mile traveled member will receive a certain percentage as a credit to another ride.
