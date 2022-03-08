

![banner.jpg](https://github.com/kamalova/Microsoft-Movie-Analysis/blob/main/images/banner.jpg)
   
# Microsoft Movie Analysis 
#### **Author**: Nurgul Kurbanali kyzy

### Project Overview
I have been charged with exploring what types of films are currently doing the best at the box office then translating those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create. Based on the datasets available have been found as a successful movie genres are fantasy, mystery and horror that production budget over the 1 million dollars. The most profitable movie directors - Francis Lawrence, Kenneth Branagh, Zack Snyder, and screenwriters - Brian Lynch, Christopher Nolan, Jack Kirby that produced more than 5 movies each. Microsoft can use this analysis to target their genres, movie directors, and screenwriters of their upcoming movie endeavors to earn the highest amount of revenue possible.

### Business Problem

Most of the big companies were creating an original video content. Microsoft also wanted to try its hand at this field by creating its own movie studio. Even though they were willing to invest, they were not sure where to start, without having enough knowledge about the movie industry. To help Microsoft, I was instructed to study which types of films are currently showing the best results at the box office, and translate my findings into actionable insights that the head of Microsoft can decide what the content of the studio shoul be. There are many aspects of films that can affect to profitability, having studied them, I based my analysis on three main factors:

* **Movie Genres** (categories that define a movie based on its narrative elements): Which genres of movie content are currently the most successful in terms of their return on investment (ROI)?
* **Movie Directors** (gives a film creative direction by guiding actors through each scene): Who are the top directors from the standpoint of movies profitability?
* **Movie Writers** (writes movie scripts or screenplays): Who are the top screenwriters in terms of the movies' average profit?
I assume that the answers to these questions are one of the main parts of the steps that should be taken into account to create the most cost-effective film in the digital world.

### Data Understanding

I used two different movie data sources for my analysis to get the broadest view of the movie industry

- The Numbers - film industry data website that tracks box office revenue in a systematic, algorithmic way. The first pre-unfiltered dataset tn_movies is in the format of compressed CSV file. Dataset contains 5782 values for movies' release date, title, production budget, domestic gross, and worldwide gross in dollars.Since most of the column attributes contained numeric values, movies' profit and return on investment has been calculated based on this dataset
- Internet Movie Database (IMDB) - website that provides information about millions of films and television programs as well as their cast and crew. The second dataset IMDB is located in a SQLite database. For the purpose of my analysis I eliminated several SQL tables that are peoples (basic information about the people that were involved to the particular movies), directors, writers, movie basics. They all were related to each other throughout the movie_id.

### Methods
I imported data from given sources, then  applied data cleaning and feature engineering techniques. Using descriptive analysis and visualization obtained the influencing aspects of films to create a profitable movie studio.

### Results
Based on the bar graph below  I will analyze the movies that production budgets starting from the 1 Million.
![fig1](https://github.com/kamalova/Microsoft-Movie-Analysis/blob/main/images/fig1.png)

#### Movie Genres
In terms of the overall movies produced *drama* genre exceeds the rest of the movie genres. Genres *comedy* and *action* are the next frequently produced movie genres.
![fig2](https://github.com/kamalova/Microsoft-Movie-Analysis/blob/main/images/fig2.png)

However, based on the Return on the Investment we can see different movie genres which are *fantasy*, *horror* and *mystery* below. 

![fig3](https://github.com/kamalova/Microsoft-Movie-Analysis/blob/main/images/fig3.png)

Interestingly, I was attracted to those top genres of films for which a high return on the investment required a smaller production budget, especially horror and mystery, which did not exceed 30 million dollars in production budget
![fig4](https://github.com/kamalova/Microsoft-Movie-Analysis/blob/main/images/fig4.png)

#### Movie Directors
![fig5](https://github.com/kamalova/Microsoft-Movie-Analysis/blob/main/images/fig5.png)
![fig6](https://github.com/kamalova/Microsoft-Movie-Analysis/blob/main/images/fig6.png)

#### Movie Directors
![fig7](https://github.com/kamalova/Microsoft-Movie-Analysis/blob/main/images/fig7.png)

I wanted to further analyze and see the production budget of the films written by *Christopher Nolan, Jack Kirb*y and *Brian Lynch*

![fig8](https://github.com/kamalova/Microsoft-Movie-Analysis/blob/main/images/fig8.png)
### Conclusion

The above analysis leads to three recommendations for Microsoft to release a successful film studio :

- Based on Microsoft's investment, I would suggest starting with movie genres with a smaller production budget of about 25 million dolllars which are **mystery** and **horror**, then increasing up to 75 million dollars with the **fantasy** genre. They are the best genres with the greatest return on investments
- For the directing of movies, I would recommend working with Francis Lawrence and **Kenneth Branagh** along with an average production volume of 1 million to 105 million. **Zack Snyder** is best suited for films with the highest production budget ove the 170 million.They all are the most profitable directors in the movie industry.
- For the production of a film in average worth up to 85 million dollars, I would recommend **Brian Lynch** as a screenwriter. Whereas, **Christopher Nolan** and **Jack Kirby** are suitable screenwriters for the movies with the higher production budget. They are all the most successful film screenwriters.
