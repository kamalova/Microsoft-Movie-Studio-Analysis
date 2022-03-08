

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

![fig1](https://github.com/kamalova/Microsoft-Movie-Analysis/blob/main/images/fig1.png)
   
### Conclusion

This project will give you a valuable opportunity to develop your data science skills using real-world data. The end-of-phase projects are a critical part of the program because they give you a chance to bring together all the skills you've learned, apply them to realistic projects for a business stakeholder, practice communication skills, and get feedback to help you improve. You've got this!
