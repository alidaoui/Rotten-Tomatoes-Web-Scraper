# Rotten-Tomatoes-Web-Scraper
Python program to scrape information from [this article](https://editorial.rottentomatoes.com/guide/140-essential-action-movies-to-watch-now/) from Rotten Tomatoes website. The webpage is titled "140 essential action movies to watch now/" and contains information about the movies including Title, Rating, and a brief description.

The program uses python's request and beautiful soup packages and the lxml parser to get the html of the webpage, then extracts the information and puts it in a Pandas DataFrame, then exports it in a csv file titled "Movies Info.csv".

This project is based on a tutorial by [365 Careers](https://www.udemy.com/user/365careers/).
