# Tweeter-Analysis-Dashboard-using-Power-BI
Power BI Twitter Analytics Dashboard built during internship in Elevance Skills to analyze tweet engagement, media performance, and interaction patterns. Implemented advanced DAX, conditional filters, median logic, and time-based visual visibility. Demonstrates skills in dashboard design, data analysis, and business logic implementation.

This project is an advanced Twitter analytics dashboard built using Power BI to analyze tweet performance, engagement behavior, and interaction patterns under complex business and time-based constraints. The dashboard provides deep insights into tweet engagement, media performance, user interaction, and conversion behavior through interactive and conditionally visible visualizations.

Project Objectives:

The goal of this project was to design and implement multiple Power BI visualizations that:

-->Analyze relationships between tweet metrics such as media views, engagements, likes, retweets, and replies

-->Compare engagement rates across different tweet conditions

-->Identify top-performing tweets based on engagement metrics

-->Categorize tweets based on interaction types such as media, links, and hashtags

-->Apply strict filtering conditions based on:

   -->Time of tweet posting
   
   -->Dashboard visibility time windows
   
   -->Odd/even logic on impressions, dates, and engagements
   
   -->Tweet word count and character count
   
   -->Removal of tweets containing specific letters
   
   -->Median-based filtering
   
   -->Weekday-only constraints

Tasks Implemented:

Task 1:
Plot a scatter chart to analyse the relationship between media engagements and media views for tweets that received more than 10 replies. Highlight tweets with an engagement rate above 5% and this graph should work only between 6PM IST to 11 PM IST apart from that time we should not show this graph in dashboard itself and the tweet date should be odd number as well as tweet word count be above 50.

Task 2:
Create a clustered bar chart that breaks down the sum of URL clicks, user profile clicks, and hashtag clicks by tweet category (e.g., tweets with media, tweets with links, tweets with hashtags). Only include tweets that have at least one of these interaction types and this graph should work only between 3PM IST to 5 PM IST apart from that time we should not show this graph in dashboard itself and the tweet date should be even number as well as tweet word count be above 40.

Task 3:
Build a chart to identify the top 10 tweets by the sum of retweets and likes. Filter out tweets posted on weekends and show the user profile that posted each tweet and this graph should work only between 3PM IST to 5 PM IST apart from that time we should not show this graph in dashboard itself and the tweet impression should be even number and tweet date should be odd number as well as tweet word count be below 30.

Task 4:
Create a line chart showing the trend of the average engagement rate over each month of the year. Separate the lines for tweets with media content and those without and this graph should work only between 3PM IST to 5 PM IST and 7 AM to 11AM apart from that time we should not show this graph in dashboard itself and the tweet engagement should be even number and tweet date should be odd number as well as tweet character count should be above 20 and need to remove tweet word which has letter 'C'.

Task 5:
Develop a visualization that compares the number of replies, retweets, and likes for tweets that have received media engagements greater than the median value. Include a filter for tweets posted in between June and August of 2020 and this graph should work only between 3PM IST to 5 PM IST and 7 AM to 11AM apart from that time we should not show this graph in dashboard itself and tweet date should be odd number and media views should be even number as well as tweet character count should be above 20 and need to remove tweet word which has letter 'S'.

Task 6:
Analyse tweets to show a comparison of the engagement rate for tweets with app opens versus tweets without app opens. Include only tweets posted between 9 AM and 5 PM on weekdays and this graph should work only between 12PM IST to 6PM IST and 7 AM to 11AM apart from that time we should not show this graph in dashboard itself and the tweet impression should be even number and tweet date should be odd number as well as tweet character count should be above 30 and need to remove tweet word which has letter 'D'.

Key Features Implemented:

Conditional Visual Visibility-

-->Visuals dynamically appear or disappear based on the current IST time using DAX time-gating logic.

Advanced Data Filtering-

-->Applied complex filtering conditions including:

-->Tweets posted during specific hours

-->Odd and even filtering on impressions, media views, and engagements

-->Word count and character count thresholds

-->Removal of tweets containing specific letters

-->Weekday-only tweet filtering

-->Median-based filtering for media engagement analysis

Engagement Analysis-

-->Compared engagement rates between tweets with app opens and without app opens

-->Analyzed engagement patterns based on media presence

Top Tweet Identificatio-

-->Identified top 10 tweets based on combined likes and retweets

-->Applied multiple constraints to isolate high-performing tweets

Interaction Analysis-

-->Compared URL clicks, profile clicks, and hashtag clicks across tweet categories

DAX and Power BI Techniques Used:

-->Calculated columns

-->Measures

-->Median calculations

-->Conditional logic using IF and SWITCH

-->Time-based visibility control using NOW() and IST conversion

-->MOD function for odd/even filtering

-->Advanced visual-level filtering

-->Dynamic grouping and categorization

Tools Used:

-->Power BI Desktop

-->DAX (Data Analysis Expressions)


Skills Demonstrated:

-->Data visualization and dashboard design

-->Advanced DAX programming

-->Business logic implementation

-->Data filtering and transformation

-->Analytical thinking and problem solving

-->Power BI dashboard optimization

Project Outcome:

Successfully developed a fully functional, condition-driven Twitter analytics dashboard that provides actionable insights while adhering to strict business and time-based logic constraints.
