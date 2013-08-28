# Reddit Top 2.5 Million

## What is this?

This is a dataset of top posts from [reddit](http://www.reddit.com). It contains the top 1,000 all-time posts from the top 2,500 subreddits, so 2.5 million posts in total. The top subreddits were determined by subscriber count and are located in the manifest file within.

Ths data was pulled between August 15-20 of August 2013.

Each file is a CSV with the related subreddit as its filename. Each CSV file contains a header line.

[A good example of the structure of this data is here.](https://github.com/umbrae/reddit-top-2.5-million/blob/master/data/serendipity.csv)

## Why?
I plan to use this for some data analysis I'm putting together for [/r/serendipity](http://www.reddit.com/r/serendipity). You're free to do whatever you like with it.

## Gotchas?

Yes, one: This only includes subreddits that are *not marked NSFW*. This is related to my particular use case, in which NSFW subreddits aren't useful for me. They'd be relatively easy to scrape if you're interested, you'll just need to get the list of NSFW subreddits from http://www.reddit.com/reddits. 

