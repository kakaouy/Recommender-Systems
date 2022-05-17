# Recommender-Systems

## - Medidas de popularidad o rankeo de items
### How Not To Sort By Average Rating
Score = Lower bound of Wilson score confidence interval for a Bernoulli parameter

We need to balance the proportion of positive ratings with the uncertainty of a small number of observations. Fortunately, the math for this was worked out in 1927 by Edwin B. Wilson. What we want to ask is: Given the ratings I have, there is a 95% chance that the “real” fraction of positive ratings is at least what? Wilson gives the answer. Considering only positive and negative ratings (i.e. not a 5-star scale), the lower bound on the proportion of positive ratings is given by:

![image](https://user-images.githubusercontent.com/22348584/168808923-9e278b0f-fe8a-45ad-baf5-b14db8aba3d2.png)


https://www.evanmiller.org/how-not-to-sort-by-average-rating.html

### - How Hacker News ranking algorithm works

Considerations: effects of gravity (G) and time (T)
Gravity and time have a significant impact on the score of an item. Generally these things hold true:

the score decreases as T increases, meaning that older items will get lower and lower scores
the score decreases much faster for older items if gravity is increased

https://medium.com/hacking-and-gonzo/how-hacker-news-ranking-algorithm-works-1d9b0cf2c08d
