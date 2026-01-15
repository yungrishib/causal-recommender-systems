# Feedback Loops and Exposure Bias in Popularity-Based Recommendation Systems

## 1. Introduction
Recommendation systems shape user attention at scale. While popularity-based ranking is widely used due to its simplicity and effectiveness, it can unintentionally create feedback loops that amplify exposure inequality. This paper investigates how such dynamics emerge even in the absence of explicit preference bias.

## 2. Related Work
Prior research has explored popularity bias, filter bubbles, and fairness in recommender systems. However, many real-world systems remain difficult to study due to data and access limitations. Simulation-based approaches provide a controlled environment to analyze these effects.

## 3. Problem Formulation
We study a recommendation system that ranks items based on historical popularity. Users interact with the top-ranked items, and these interactions are fed back into future ranking decisions. We examine whether this process leads to systematic exposure disparities between item groups.

## 4. Methodology
We construct a simulated environment consisting of users and items divided into two groups. At each round, items are ranked by popularity score, users interact with the top-K items, and popularity is updated accordingly. Exposure counts are tracked over multiple rounds to observe long-term dynamics.

## 5. Experiments
We run multiple recommendation rounds under identical initial conditions. Exposure levels for each item group are recorded after every round to measure how ranking decisions evolve over time.

## 6. Results
Our results show that small initial popularity differences grow over time, resulting in increasing exposure inequality between item groups. The exposure gap widens consistently across rounds, indicating a self-reinforcing feedback loop.

## 7. Discussion
These findings suggest that popularity-based recommenders can introduce systemic bias without explicit discriminatory signals. Such effects raise concerns for fairness and diversity in real-world systems.

## 8. Limitations and Future Work
This study uses a simplified simulation and does not model real user behavior or
complex recommendation architectures. The goal was to isolate algorithmic
feedback effects rather than achieve realism.

Future work could include incorporating public datasets, modeling heterogeneous
user preferences, or testing fairness-aware ranking strategies.


## 9. Conclusion
We demonstrate that feedback loops in recommendation systems can significantly amplify exposure bias. Future work should explore causal and fairness-aware ranking mechanisms to mitigate these effects.

## References
