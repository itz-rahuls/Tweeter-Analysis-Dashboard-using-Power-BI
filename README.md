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

Key Features Implemented

Conditional Visual Visibility:
-->Visuals dynamically appear or disappear based on the current IST time using DAX time-gating logic.

Advanced Data Filtering
-->Applied complex filtering conditions including:
-->Tweets posted during specific hours
-->Odd and even filtering on impressions, media views, and engagements
-->Word count and character count thresholds
-->Removal of tweets containing specific letters
-->Weekday-only tweet filtering
-->Median-based filtering for media engagement analysis

Engagement Analysis
-->Compared engagement rates between tweets with app opens and without app opens
-->Analyzed engagement patterns based on media presence

Top Tweet Identification
-->Identified top 10 tweets based on combined likes and retweets
-->Applied multiple constraints to isolate high-performing tweets

Interaction Analysis
-->Compared URL clicks, profile clicks, and hashtag clicks across tweet categories

DAX and Power BI Techniques Used
-->Calculated columns
-->Measures
-->Median calculations
-->Conditional logic using IF and SWITCH
-->Time-based visibility control using NOW() and IST conversion
-->MOD function for odd/even filtering
-->Advanced visual-level filtering
-->Dynamic grouping and categorization

Tools Used
-->Power BI Desktop
-->DAX (Data Analysis Expressions)


Skills Demonstrated
-->Data visualization and dashboard design
-->Advanced DAX programming
-->Business logic implementation
-->Data filtering and transformation
-->Analytical thinking and problem solving
-->Power BI dashboard optimization

Project Outcome
Successfully developed a fully functional, condition-driven Twitter analytics dashboard that provides actionable insights while adhering to strict business and time-based logic constraints.
