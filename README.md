# Social Media Data Science Pipeline (CS 515)

![bu](/img/bulogo.png)

## Project-2 Implementation
> Investigating The Foremost Factors Determining Artists’ Success

### Group Name
> Chestnut

### Work distribution
### Implementation
- Disha Shetty (dshetty3@binghamton.edu)
- Yashaswi Hasarali (yhasara1@binghamton.edu)
### Documentation
- Om Fale (ofale1@binghamton.edu)


### Introduction

In the ever-evolving landscape of the music industry, our project delves into the intricate dynamics that define an artist's journey in this era of unprecedented change. Leveraging a fusion of social media analysis and data science methodologies, we tap into the expansive realms of Reddit and Spotify. Through Reddit, a diverse online community, we unravel fan discussions, reviews, and opinions, discerning patterns in engagement and sentiment. Simultaneously, we harness Spotify's vast streaming data, offering insights into play counts, follower growth, and playlist placements. Join us on this exploration as we gather real-time music-related data, unveiling the pulse of emerging trends and popular artists within a specified timeframe.

## Description

* For this project, we have thought about and have answered three research questions/areas based on our datasets and the type of data
we have gathered. Our research objectives shall revolve around the factors influencing the popularity of artists based on data
collected from Reddit and Spotify. 
We already have collected relevant information from project 1 using posts of subreddits r/Spotify, r/Music, r/Popheads and official subreddits of artists data. As far for Spotify we have used playlist id () to get the daily top hits and the artists details to get to know the genre they follow to and their popularity.  Now it is time for us to play with these data.

* Further, we have answered the following research questions:

Ques. Is there a correlation between the level of activity on artist specific subreddits (e.g., official subreddits) and the artist’s success on Spotify, measured by metrics such as number of top hits and overall popularity?
* We have extracted data from artists_posts and artists_details and from artists_posts we have plotted the graph as to which artists get how many number of posts per day. Additionally, from Spotify API, we get the corresponding artists details and plot the graph and check the correlation coefficient for Artists: Popularity vs Number of Posts and study what will be the factors and whether does the spotify data goes hand in hand with the engaging number of posts related to the artists.
#If the coefficient is positive, it suggests a positive correlation (as the number of posts increases, popularity tends to increase).
#If the p-value is less than 0.05, you can reject the null hypothesis that there is no correlation.

Ques. How do the music genres discussed on Reddit correlate with the genres that users actually listen to on Spotify, and can we identify any trends in genre preferences from these discussions?
* By analyzing post frequency, we identified the top genres based on the occurrences of songs and their respective genres in Reddit posts. It's important to note that not all subreddits align perfectly, given the diverse user base discussing various genres like country, rock, and less mainstream songs. However, our analysis, reflected in the plotted graphs, reveals that pop and rap songs dominate discussions, garnering the highest number of comments. These genres seem to have a significant presence and engagement within the Reddit community according to our findings.


Ques. To what extent can the engagement metrics from Reddit (e.g., post popularity, comments, sentiment) and Spotify (e.g., daily top hits, artist details, popularity index) predict the commercial success and overall popularity of artists, and are there specific patterns or trends that indicate a higher likelihood of success within the music industry (sentiment analysis on the comments) ?
* Extensive analysis, encompassing data understanding, cleaning, and plotting, was conducted to address the research question. Utilizing sentiment analysis of comments and employing word clouds played a pivotal role in comprehending the patterns that underlie the phenomenon in question. Through thorough examination, it has become evident that established artists such as Taylor Swift, Travis Scott, The Weeknd, Drake, and SZA are poised to emerge as the top trending artists on Spotify by the end of the year, considering all the factors taken into consideration.


### Data Sources
- Reddit API, Spotify API, ModerateHateSpeach

### Pre-requisites
This project is built on top project-1-implementation-chestnut, so all the necessary installations have to be done which were required for Project 1. Please refer to the README.md file of implementation folder of project 1 or navigate to the path https://github.com/2023-Fall-CS-415-515/project-1-implementation-chestnut/blob/main/README.md


#### Building and running application

Refer README.md of project 1



#### Configuration
credentials.env - credentials configuration

### Changes from Implementation 1
All the sensitive data are added into the config file (.env) file for security purposes.

### System requirement

| Name | Requirement |
| ------ | ------ |
| Memory | 8Gb |
| OS | Linux |

#### References 

[1] Reddit API Documentation. https://www.reddit.com/dev/api/

[2] ModerateHatespeech Documentataion. https://moderatehatespeech.com/docs/

[3] Spotify API Documentation. https://developer.spotify.com/documentation/web-api

[4] Matplotlib Library Documentation https://matplotlib.org/

[5] Textblob Library Documentation. https://textblob.readthedocs.io/en/dev/

[6] WordCloud Library Documentation. https://pypi.org/project/wordcloud

[7] Seaborn Library Documentation. https://seaborn.pydata.org/

[8] Spotipy Library Documentation. https://spotipy.readthedocs.io/en/2.22.1/#api-reference

[9] Plotly Library Documentation. https://plotly.com/python/getting-started/#jupyterlab-support

[10] Tabulate Library Documentation. https://pypi.org/project/tabulate/
