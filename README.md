### Data-driven insights for successful Movie Studio

![image](https://github.com/StephenMulingwa/Group_Project/blob/bbe09d12641a54591d8cbb385c8dc616afb7c2ce/Cinema.png)


**INTRODUCTION**

The movie industry is highly competitive, with countless production companies vying for the attention of global audiences. After intensive research, we were tasked to research the current film industry trends to assist in directing the company's upcoming film production endeavour. Knowing what kinds of movies are doing well at the box office will be crucial to our new movie studio's success as more businesses venture into producing original video content. We will find important patterns and trends in audience preferences by examining recent box office data. To help the studio head make well-informed decisions regarding the genres, themes, and formats that are most likely to appeal to viewers and optimize our studio's success, these insights will be converted into practical insights. 


## Business Understanding  
The project focuses on analyzing the film industry to guide a new movie studio in optimizing box office performance. It involves researching current trends and audience preferences through exploratory data analysis of recent box office data. Key objectives include identifying successful genres, understanding how genre influences revenue and ratings, and determining optimal budgets and release timings. By deriving actionable insights from these analyses, the project aims to help the studio make informed decisions on film production strategies to increase the likelihood of financial success in a competitive market.

**Business Questions for the upcoming project**
1.	What genres are currently the most successful at the box office? 
2.	How does genre influence revenue and viewer ratings?
3.	How do genre and ratings impact a movie’s revenue?
4.	What patterns can be observed in successful movies, and how can these patterns inform production choices for a new studio?
5.	Is there an optimal budget range or release period that aligns with higher box office returns?

## Project Overview
Understanding the elements and factors that affect a movie’s performance has become essential for newcomers to the market as the entertainment sector expands. Our company intends to launch a new movie studio to optimise box office performance by determining the key factors that impact a movie’s success. The business will be able to make well-informed decisions about the types of films to make, the best times to release them, and budget allocations. 

## Problem Statement
There are many movies released annually, making the film industry extremely competitive. Numerous factors can impact a movie’s performance, and not all movies are financially successful. The genre, release date, budget, ratings and production company are some of the factors that can greatly impact a film's success or failure. However, it is difficult for the business to come up with a plan that boosts the possibility of creating box office hits if these influencing factors are not well understood.
For this project, we will use exploratory data analysis to generate insights for a business stakeholder.

### Data Understanding
The dataset was sourced from various platforms including Box Office Mojo, IMDb, Rotten Tomatoes, The Movie DB, and The Numbers, and consists of movie-related data in different formats, such as CSV, TSV, and a SQLite database. 
Key entries include the "movie_basics" and "movie_ratings" tables from the IMDb database and box office gross data from the compressed CSV file.
The dataset includes 1,764 films and 12 columns, covering titles, studios, runtime, genres, popularity, release dates, ratings, budgets, and gross revenues.
Analyzing production budgets, gross earnings, and audience ratings will reveal trends to guide the new movie studio's genre and theme decisions
Insights drawn from the dataset will enable the studio to align its production strategy with market demands, increasing the likelihood of creating successful original video content.


### Data Analysis
Drama is the most prevalent genre, with 897 entries. This suggests a strong audience interest in character-driven stories and emotional narratives, making it a staple in film production.
There remains a healthy diversity of genres that cater to varied tastes, although some traditional genres like westerns and musicals are underrepresented. This trend suggests filmmakers continue to explore a wide range of narratives while also gravitating towards proven successes in more popular genres.
The distribution of movie runtimes shows that the average runtime is approximately 100 minutes, with most films falling between 90 and 120 minutes, indicating a wide range of runtimes in the dataset.
The average ROI shows that the Sport genre is the most profitable, with an ROI of about 15.23, followed by Horror at 12.52 and Romance at 9.12. In contrast, genres like War (1.68) and News (0.98) have much lower returns, highlighting big differences in profitability.
A strong positive correlation between production budget and worldwide gross suggests that higher production budgets generally result in higher worldwide earnings across the different studios.

### Data Visualizations

This is a visualization that portrays seasonal trends in Worldwide Box office revenue.
![image](https://github.com/StephenMulingwa/Group_Project/blob/aeb221ecb9e53bba8f3a1aa84e038ad40d5fce73/WhatsApp%20Image%202024-10-29%20at%2022.45.08.jpeg)





This is a visualization that portrays the comparison of the average Return on Investment(ROI) by Genre.
![image](https://github.com/StephenMulingwa/Group_Project/blob/9a6d5208ba40f1e3233d4756f49c29214542ddae/Average%20ROI%20by%20Genre.png)




This is a visualization that portrays the distribution of movie genres. A comparison of the number of movies and genres.
![image](https://github.com/StephenMulingwa/Group_Project/blob/7572ccd7c6be2efb593e8b2839ce34c897bed9ff/Distribution%20of%20Movie%20Genres.png)





This is a visualization that portrays the distribution of runtime minutes.
![image](https://github.com/StephenMulingwa/Group_Project/blob/a77480debf2b271b99dfcfa9d0c7f8473a84017c/Distribution%20of%20the%20Runtime%20minutes.png)




This is a visualization that portrays the scatterplot on correlation.
![image](https://github.com/StephenMulingwa/Group_Project/blob/3c836b7e42b05b63900c663b7f19172e3c9bd6f5/Scatterplot%20on%20correlation.png)




This is a visualization that portrays a comparison of the production budget and worldwide gross by studios.
![image](https://github.com/StephenMulingwa/Group_Project/blob/406558a8d8382c13d124faea316e579fe13c4e3b/WhatsApp%20Image%202024-10-29%20at%2022.44.52.jpeg)


### RECOMMENDATIONS
- It is clear that Drama, Comedy, and Action genres are the most successful because they have significantly more films produced compared to other genres, suggesting high market demand.
- Genres like Sport, Sci-Fi, and Fantasy achieve high gross revenues, strong viewer ratings, and favourable ROIs, while genres like War and News have lower financial returns and ratings, making 
  them less attractive for investment.
- Seasonal movie releases timed during some months tend to yield high revenues, while certain months experience a significant drop in audience engagement. This can help in planning the release 
  schedules.
- The strong link between domestic and worldwide gross shows that how well a film does at home is important, highlighting the need for good marketing and audience engagement in the domestic 
  market.

### CONCLUSION
- It is clear that Drama, Comedy, and Action genres are the most successful because they have significantly more films produced compared to other genres, suggesting high market demand.
- Genres like Sports, Sci-Fi, and Fantasy achieve high gross revenues, strong viewer ratings, and favourable ROIs, while genres like War and News have lower financial returns and ratings, 
  making them less attractive for investment.
- Seasonal movie releases timed during some months tend to yield high revenues, while certain months experience a significant drop in audience engagement. This can help in planning release 
  schedules.
- The strong link between domestic and worldwide gross shows that how well a film does at home is important, highlighting the need for good marketing and audience engagement in the domestic 
  market.



For the tableau visualizations, click here 👇🏾https://public.tableau.com/views/groupproject_17302300046460/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
