📘 Repository Description  
Instagram Relational Database & Analytical Queries in SQL. This project implements a fully normalized relational database schema for an Instagram-like social media platform. It models core entities—users, photos, hashtags, comments, likes, follows, and tagged photos—allowing for in-depth analysis of user behavior, engagement trends, and content performance. The repository includes complete table definitions, populated sample datasets, and analytical SQL queries designed to address real-world platform metrics such as active users, popular hashtags, follower growth, and viral posts.

📂 Schema & File Overview
1. Users Table.sql

Stores registered user information with unique identifiers and account creation dates.  
Key Uses: Demographic aggregation, activity tracking, account growth trends.

2. Photos Table.sql

Contains user-uploaded images linked to posting users and timestamps.  
Key Uses: Upload frequency analysis, post timeline trends.

3. Hashtags Table.sql

Predefined set of popular hashtags.  
Key Uses: Tag popularity, trend monitoring, thematic categorization.

4. Photo_Tags Table.sql

Junction table linking photos with hashtags.  
Key Uses: Hashtag co-occurrence analysis, topical clustering.

5. Comments Table.sql

Captures text comments linked to both users and photos.  
Key Uses: Engagement depth analysis, sentiment tagging, interaction mapping.

6. Likes Table.sql

Records user likes on photos.  
Key Uses: Engagement rate calculation, identifying viral content.

7. Follows Table.sql

Represents follower-followee relationships between users.  
Key Uses: Social graph analysis, influencer identification.

8. Instagram.sql

Master script containing the schema creation and advanced analytical queries, such as:  

Oldest users and most engaged members  
Detecting inactive or bot-like accounts  
Top-performing posts by likes and comments  
Popular hashtags and content themes  
Relationship-based user suggestions  

🔍 Key Features Demonstrated

Fully normalized schema with referential integrity and foreign key constraints  
Complex joins for multi-entity relationship queries  
Aggregations & subqueries for advanced analytics  
Activity pattern analysis for engagement insights  
Realistic sample data for immediate testing and dashboard integration  

This dataset and schema are ideal for:  

Portfolio demonstration of SQL schema design and query optimization  
Interview preparation involving relational data modeling  
Building BI dashboards on top of social media datasets  
