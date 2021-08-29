# Fandango-2015-Movie-Ratings---Legit-or-Bias-
[Click here to see the Jupyter Notebook](Fandango+Movie+Ratings+II.ipynb)
This report tests whether Fandango 2015 movie ratings are bias.

This guided project ties in with an article ([here](https://fivethirtyeight.com/features/fandango-movies-ratings/ 'here')) titled, 'Be Suspicious Of Online Movie Ratings Especially Fandango’s', written by Walt Kickey in 2015. You can access the data used for the article [here](https://github.com/fivethirtyeight/data/tree/master/fandango 'here'). Walt explains that he was prompted by a colleague to investigate the validity of Fandango's movie ratings. Walt gathered movie rating data on movies released in 2015 up to August 2015 from the following movie rating sources:

- Rotten Tomatoes Critics
- Rotten Tomatoes Users
- Metacritic Critics
- Metacritic Users
- IMDb Users
- Fandango

To improve uniformity of the raw data, Walt made a judgement call to focus primarily on movies that had 30 or more user reviews. These would be regarded as 'popular movies'. As Walt began to dig deeper in his analysis, he observed the following regarding Fandango ratings:

- none of the 209 popular movies had below a 3-star rating.
- seventy-eight percent had a rating of 4 stars or higher.
- when Fandango averages user ratings on its website, they never round the average down.
- there were times when Fandango’s rounding system added a half-star to the film’s rating.
- for the 209 popular movies, the average movie gained 0.25 stars from this rounding.

**So, if there is purpose in the Fandango ratings being manipulated with a positive bias, what's in it for them? Simple: Fandango sells tickets directly to consumers. What better way to potentially increase ticket sales than by showing higher movie ratings.**

When Walt brought his observations to light via his article and asked Fandango for explanation, their response basically was, “There appears to be a software glitch on our site with the rounding logic of our five star rating system, as it rounds up to the next highest half star instead of the nearest half star.”

The objective of this project is to determine whether Fandango corrected their movie rating flaws.

I did this by comparing the movie rating results from (2015) and from (2016) after their response; "We plan to fix the rounding algorithm on our website as soon as possible".

**In the analysis process, I used a "pre-test post-test control group" method. I was able to obtain a legitimate "control group"! I took a different approach than what was suggested in the guidelines.**

## FIND OUT THE ANSWER!

[Click here to see the pdf File](Fandango+Movie+Ratings+II.pdf) (this can be downloaded).
