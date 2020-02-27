# Poker-preflop-hand-rank-scraping-to-csv
A simple web scraper to generate a csv of the rank of preflop hands in poker.

There is a lot of libraries/algorthims on poker rank hands.
But all of then, that I have tested on a fast research through the internet doesn't rank pre-flop hands.
I think the main reason is that most of this libraries/algorthims are used for Poker-Bots and most of then use a pre-defined technique for preflop game and don't need to rank their hands.

In case someone wants to use ranked hands for preflop I created this simple [notebook](https://github.com/BrenoCPimenta/Poker-preflop-hand-rank-scraping-to-csv/blob/master/preflopCrawler.ipynb) that scrapes this [website](https://www.preflophands.com/), in wich the information is pretty straight foward.

## Download
If you want to just download the CSV File is here.

## Organization
* 1ªColumn: Rank 1 to 169<br><br>
* 2ºColumn: Cards<br><br>
* 3ºColumn: 
    * 's': is suited;
    * 'o': isn't suited;
    * 'p': it's a pair;
