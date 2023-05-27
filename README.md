Movie Insights: Exploring Box Office Performance and Ratings(2013-2019)

![image](https://github.com/sogodongo/Phase-1-Project/assets/103502854/940eb443-2445-4739-9395-bcd21f4d33f3)


a) Introduction


Microsoft is a multinational technology company known for its wide range of software, hardware, and services. Founded in 1975 by Bill Gates and Paul Allen, Microsoft has played a pivotal role in shaping the digital landscape and revolutionizing the way people interact with technology. With iconic products such as Windows, Office, and Xbox, Microsoft has established itself as a global leader in the technology industry. The company's mission is to empower individuals and organizations worldwide to achieve more through the power of innovative technology solutions. Microsoft's commitment to innovation, coupled with its strong focus on cloud computing, artificial intelligence, and digital transformation, has positioned it as a key player in the modern digital era. Continually striving to push the boundaries of what is possible, Microsoft remains at the forefront of technological advancements, driving innovation and transforming industries across the globe.

In an effort to expand its business portfolio, Microsoft intends to venture into the movie industry by establishing a new movie studio. However, to navigate this highly competitive industry and maximize their chances of success, Microsoft needs a comprehensive understanding of the types of films that resonate with audiences and perform well at the box office. This project aims to address this knowledge gap by conducting an in-depth analysis of data from various authoritative sources in the movie industry, including Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB, and The Numbers. By leveraging this data, the project seeks to identify successful film genres and provide actionable insights that can guide Microsoft's decision-making process when it comes to selecting the types of films to produce

b) Problem Statement
The organization lacks a comprehensive understanding of the factors that contribute to the success and profitability of films in the highly competitive movie industry. This knowledge gap hinders their ability to make informed decisions regarding film production, genre selection, release strategies, and resource allocation. To address this challenge, the main objective of this project is to analyze various aspects of the movie industry, including box office performance, seasonal patterns in successful movie releases, genre popularity and trends, and the impact of movie runtime, genres, and studios on ratings. By gaining insights into these factors, Microsoft aims to make data-driven decisions that will maximize their chances of producing successful films and achieving financial success in the market.

c) Main Objective
To gain insights and make informed decisions regarding box office performance, seasonal patterns in successful movie releases, genre popularity and trends, and the impact of movie runtime, genres, and studios on ratings. This objective aims to provide valuable information for Microsoft to understand and navigate the movie industry more effectively.

d) Specific Objectives
i. Analyze Box Office Performance
Explore "tn.movie_budgets.csv" file to analyze the box office performance of different films. Examine the domestic and international gross earnings and budgets of differentt movie genres. Identify the highest-grossing films and compare their performance across genres. Determine the most profitable genres that have a higher likelihood of financial success.

ii. Assessing Seasonal Patterns in Successful Movie Releases
Explore the "tn.movie_budgets.csv" file to understand the the number of successful movies releases overtime based on a positive return on investements(ROI).Assessing the most successful months to release movies.

iii. Assessing Genre Popularity and Trends
Analyze the genre distribution in the "movies_data" file to understand the popularity of different genres among filmmakers and audiences.

iv. Analyzing the Impact of Movie Runtime,Genres and Studios on Ratings
Utilize the "rt.movie_info.tsv" and "rt.reviews.tsv" files to analyze audience ratings of films. Analyze the impact of Studios on Movie Rating. Identify genres that receive positive audience feedback and have a higher likelihood of success based on ratings. Investigate whether there is a significance correlation between movie runtime and ratings.Confirm the recent movie trends.

e) Experimental Design
Data Collection
Reading the data
Exploring and Reprocessing Data
Data Analysis
Conclusions and Recommendations
f) Data Understanding
The movie data used in this project was obtained from Box Office Mojo,TheMovieDB,IMDB,Rotten Tomatoes and The Numbers.

The websites contain the following datasets:

tn.movie_budgets.csv.gz also has 5782 rows abd 8 columns for financial & studio information for different movies and studios including their production budgets, domestic and worldwide gross earnings, and release dates.
tmdb.movies.csv has 25497 rows 10 columns containining information about genre information and popularity rating for different movies
rt.movie_info.tsv has 54432 rows and 8 columns of ratings,reviews and release dates for different movies
rt.movie_info.tsv 1560 rows and 12 columns of runtime and genre information for different movies
No other external datasets were used in this project. The focus was primarily on analyzing the relationships between movies and their corresponding genres,their budgets, earnings ,release dates and runtime.

Here is a snippet of the data used:

image-3.png



Data Cleaning
Out of the several datasets that were collected, only some features and rows are relevant to the process. Therefore, in this step, the features that are not required from each dataset were dropped. The remaining datasets were then joined. 


 Data Analysis
I). Analyzing Box Office Performance
a) Analyzing the top performing movies in box office in terms of gross domestic and worldwide earnings.
b) Analyzing the most profatble movie genres


II. Assessing Seasonal Patterns in Successful Movie Releases
a) Assessing the number of successful movies releases overtime based on a positive return on investements(ROI)
b) Assessing the most successful months to release movies

III. Assessing Genre Popularity and Trends
a) Assessing the most popular genres

IV. Analyzing the Impact of Movie Runtime,Genres and Studios on Ratings
a) Analyzing the impact of movie genres on rating
b) Exploring the Relationship between Runtime and Movie Rating
c) Exploring the impact of Studios on Movie Rating

Conclusions
- Genres such as Animation and Adventure demonstrate strong financial success, with the highest total gross earnings. Additionally, genres like Fantasy, Family, Science Fiction, Action, Comedy, War, Romance, and Crime also perform well at the box office. Family movies stand out as the most profitable, followed by genres like Animation, Action, Adventure, Fantasy, and Science Fiction.

- The number of successful movie releases has generally increased over the years, with fluctuations. The industry experienced notable growth, particularly in the 1980s, 1990s, and early 2000s. However, recent years (2017-2019) have shown a decline in the number of successful movie releases, possibly due to shifting audience behavior and increased competition.

- December and October emerge as popular months for successful movie releases, and there are seasonal patterns indicating higher releases during the spring and summer seasons. Planning movie releases to align with these periods can potentially attract larger audiences.

- Certain genre combinations, such as Adventure, Action, and Fantasy, exhibit the highest popularity scores, indicating a strong appeal and capturing audience attention. Exploring these genre combinations can enhance the chances of creating popular and well-received movies.

- The choice of studio significantly impacts movie success and perception. Studios like The Weinstein Company and Lionsgate/Roadside Attractions have higher average ratings, reflecting their ability to produce well-received films. Collaborating or partnering with successful studios can contribute to the overall success of movie projects.

- Movie runtime does not have a meaningful relationship with audience ratings. This suggests that factors other than runtime, such as engaging storytelling, compelling characters, and effective marketing strategies, play a more significant role in influencing audience ratings.

Recommendations
- Invest in genres that have demonstrated strong financial success, such as Animation, Adventure, Fantasy, Family, Science Fiction, Action, Comedy, War, Romance, and Crime. These genres have consistently performed well at the box office and offer higher chances of financial success.

- Analyze audience preferences and strategically plan movie releases during popular months like December and October, as well as during the spring and summer seasons. These periods have shown higher success rates for movie releases, attracting larger audiences.

- Collaborate or partner with successful studios like The Weinstein Company, Lionsgate/Roadside Attractions, or other independent studios known for producing high-rated films. Working with established studios can enhance the overall success and perception of movies.

- Focus on factors beyond runtime to enhance audience ratings.For example,you could engage in compelling storytelling, develop memorable characters, and implement effective marketing strategies.

- Stay updated with evolving audience behavior and industry trends. Continuously monitor and adapt to changing preferences and expectations of moviegoers. Remaining competitive in the dynamic movie industry requires being responsive to audience demands and industry shifts

Further Improvement Ideas
- Explore additional factors that influence movie success, such as marketing budget, release strategy, cast and crew, and critical acclaim.

- Analyze regional or international trends to identify opportunities for global market penetration.

- Incorporate audience demographic data to tailor movie offerings and marketing campaigns to specific target audiences.

- Conduct market research or surveys to understand audience preferences and expectations more comprehensively.

