**Mosteller review**

Evaluation of the probability of the best team winning in various sports finals (NBA, NHL), based on the [Mosteller](https://math.mit.edu/classes/18.095/2016IAP/lec9/Sports_Mosteller1952_WorldSeries.pdf) model developed for MLB World Series.

_Probability Model_

Each game in the finals (best-of-7) is modeled as a Bernoulli trial where the better team has a probability 𝑝>0.5 of winning (_unfair coin_)). The final outcome is determined by summing up the Bernoulli trials (i.e., the games).
Mosteller’s model estimates the likelihood of a certain win-loss sequence for the better team (e.g., 4-0, 4-1, etc.), using Maximum Likelihood Estimation (MLE) to find the best 𝑝.

_Case Study_
We dynamically evaluated the probability of the better team winning NBA and NHL finals from 1980 onwards by starting with a 10-year window, progressively adding one year at a time, and recalculating the probability to track how league decisions and events impacted competitive balance over time.


