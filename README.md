# Recommender-Systems

## Medidas de popularidad
### How Not To Sort By Average Rating
Score = Lower bound of Wilson score confidence interval for a Bernoulli parameter

We need to balance the proportion of positive ratings with the uncertainty of a small number of observations. Fortunately, the math for this was worked out in 1927 by Edwin B. Wilson. What we want to ask is: Given the ratings I have, there is a 95% chance that the “real” fraction of positive ratings is at least what? Wilson gives the answer. Considering only positive and negative ratings (i.e. not a 5-star scale), the lower bound on the proportion of positive ratings is given by:

![image](https://user-images.githubusercontent.com/22348584/168808923-9e278b0f-fe8a-45ad-baf5-b14db8aba3d2.png)


https://www.evanmiller.org/how-not-to-sort-by-average-rating.html
