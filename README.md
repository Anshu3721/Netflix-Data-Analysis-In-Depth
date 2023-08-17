# Exploratory Data Analysis on Netflix Dataset Dashboard

## Business Problem
The business problem for data analysis is to harness insights from Netflix's content landscape to inform strategic decision-making and content curation. The goal is to optimize content selection, enhance viewer engagement, and align releases with viewer preferences, ultimately driving growth and maintaining a competitive edge in the streaming industry.

## Summary of Data
The dataset used for this Netflix EDA project is a comprehensive collection of data related to movies and TV shows available on the Netflix streaming platform. It includes information such as title, release year, genre, duration, IMDb ratings, user reviews, and viewer demographics. with the help of this dataset we can conduct an in-depth analysis of content trends, user behavior, and sentiment.

Dataset link: https://www.kaggle.com/datasets/swatikhedekar/exploratory-data-analysis-on-netflix-data?select=netflix_titles_2021.csv

## Attributes Information

- `show_id`     : unique id of each show (not much of a use for us in this notebook)
- `type`        : The category of a show, can be either a Movie or a TV Show
- `title`       : Name of the show
- `director`    : Name of the director(s) of the show
- `cast`        : Name of actors and other cast of the show
- `country`     : Name of countries the show is available to watch on Netflix
- `date_added`  : Date when the show was added on Netflix
- `release_year`: Release year of the show
- `rating`      : Show rating on netflix
- `duration`    : Time duration of the show
- `listed_in`   : Genre of the show
- `description` : Some text describing the show

## Some Information about ratings
#### Children
- `TV-Y`  :Designed to be appropriate for all children
- `TV-Y7` :Suitable for ages 7 and up
- `G`     :Suitable for General Audiences
- `TV-G`  :Suitable for General Audiences
- `PG`    :Parental Guidance suggested
- `TV-PG` :Parental Guidance suggested

#### Teens
- `PG-13` :Parents strongly cautioned. May be Inappropriate for ages 12 and under.
- `TV-14` :Parents strongly cautioned. May not be suitable for ages 14 and under.

#### Adults
- `R`     :Restricted. May be inappropriate for ages 17 and under.
- `TV-MA` :For Mature Audiences. May not be suitable for ages 17 and under.
- `NC-17` :Inappropriate for ages 17 and under


## Visualisation and Insights
### Content Overview:
- Distribution of Movies and TV Shows <br>

![image](https://github.com/Anshu3721/Netflix-Data-Analysis-In-Depth/blob/main/movies%20and%20tv%20shows.png)<br>
**The dataset contains 70% movies and 30% TV shows, indicating a stronger presence of movies on Netflix. This distribution highlights Netflix's focus on offering a diverse range of content types to cater to different viewer preferences.**<br>
<br>

- Top 10 Genres on Netflix <br>

![image](https://github.com/Anshu3721/Netflix-Data-Analysis-In-Depth/blob/main/top%2010%20genres.png)<br>
**The top 10 genres on Netflix include International Movies, Drama, Comedy, Action, Thriller, and Documentary, among others. This reveals that viewers enjoy a mix of genres, with Drama and Comedy leading the way. This diversity ensures that users with varying interests can find content tailored to their preferences.**<br>
<br>

- Genres Distribution by Content Type <br>

![image](https://github.com/Anshu3721/Netflix-Data-Analysis-In-Depth/blob/main/genres%20distribution%20of%20moves%20and%20tv%20shows.png)<br>
**For movies and TV Shows, Drama and Comedy are the dominant genres. Understanding these genre preferences aids in content curation.**<br>
<br>

- Top 10 Directors <br>

![image](https://github.com/Anshu3721/Netflix-Data-Analysis-In-Depth/blob/main/Top%2010%20directors.png)<br>
**Rajiv Chilaka stands out as the most active director, having worked on 19 movies and TV shows for Netflix. Directors like Raul Campos and Jan Suter are also quite prolific. This indicates that some directors have played a big role in creating content for Netflix. They might have built a strong following of fans who enjoy their work.**<br>
<br>

- Top 10 Actors <br>

![image](https://github.com/Anshu3721/Netflix-Data-Analysis-In-Depth/blob/main/Top%2010%20actors.png)<br>
**Anupam Kher has appeared in 39 movies and TV shows, making them the most frequently featured actor on Netflix. Rupa Bhimani and Takahiro Sakurai also appear frequently. Recognizable actors can attract audiences, contributing to the popularity of content.**<br>
<br>

### Regional Analysis
- Top 10 Countries <br>

![image](https://github.com/Anshu3721/Netflix-Data-Analysis-In-Depth/blob/main/Top%2010%20Countries.png)<br>
**The top three countries in terms of content availability are the United States, India, and the United Kingdom. This highlights Netflix's global reach and its efforts to cater to diverse regional audiences.**<br>
<br>

- Rating Distribution among Top 10 Countries <br>

![image](https://github.com/Anshu3721/Netflix-Data-Analysis-In-Depth/blob/main/rating%20vs%20countries.png)<br>
**Ratings like TV-MA (Mature Audience) and TV-14 (Teens) are prevalent across most top countries. However, the United States has a higher proportion of TV-MA content and India has higher Proportion of content related to teens, possibly reflecting different cultural sensitivities towards content suitability.**<br>
<br>

### Content Release and Viewer Engagement Analysis
- Content Addition over Time (Added Year) <br>

![image](https://github.com/Anshu3721/Netflix-Data-Analysis-In-Depth/blob/main/movies%20and%20tv%20shows%20w.r.t%20added_year.png)<br>
**Content additions on Netflix have increased steadily, showing a notable surge recently, reflecting Netflix's commitment to meeting viewer demands. After 2015, more movies than TV shows were released. Post-2020, movie releases declined..**
<br>

- Day-wise Content Release <br>

![image](https://github.com/Anshu3721/Netflix-Data-Analysis-In-Depth/blob/main/day%20wise%20content.png)<br>
**Fridays have the most new content on Netflix. This hints at well-thought-out timing for releasing content. It might match when people like to watch, making it a smart strategy.**
<br>

- Month-wise Content Release <br>

![image](https://github.com/Anshu3721/Netflix-Data-Analysis-In-Depth/blob/main/month%20wise%20content.png)<br>
**July stands out as the month with the highest content additions. This could be related to seasonal trends or planned releases to coincide with holidays or events that attract higher viewership.**
<br>

###  User Behavior Analysis
- Top 5 TV Shows and Movies Duration <br>

![image](https://github.com/Anshu3721/Netflix-Data-Analysis-In-Depth/blob/main/top%205%20movies%20%26%20tv%20shows%20by%20duration.png)<br>
**People tend to enjoy longer content, seen in Tv shows with just one season and movies around 90 minutes. This matches binge-watching habits, showing a preference for deep, immersive stories.**
<br>

- Top Ratings for TV Shows and Movies <br>

![image](https://github.com/Anshu3721/Netflix-Data-Analysis-In-Depth/blob/main/top%203%20ratings.png)<br>
**Content with adult ratings has earned high viewer ratings, indicating quality and satisfaction. High-rated content tends to draw more viewers and enhance positive user experiences.**
<br>
