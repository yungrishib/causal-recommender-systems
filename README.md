##Research Context
This project was developed as an independent undergraduate research exercise to study feedback loops and exposure bias in recommender systems using simulation-based analysis. The goal is conceptual understanding rather than production deployment or empirical user modeling.

# Feedback Loops and Exposure Bias in Recommendation Systems

This project is a small research experiment I conducted to understand how
recommendation algorithms can influence visibility and fairness over time.

While studying recommendation systems, I became curious about a simple question:
Can popularity-based ranking alone create inequality, even if users are neutral?

To explore this, I built a simulation that models users interacting with ranked
items over multiple rounds and observed how exposure changes over time.

## What this project does
- Simulates a popularity-based recommender system
- Models repeated recommendation rounds
- Tracks exposure of different item groups
- Visualizes how feedback loops amplify bias

## Why this matters
Most real-world platforms rely on engagement-based ranking.
This project shows that even without biased users, algorithmic feedback loops
can systematically amplify inequality.

## Important note
This is a simplified simulation and does not represent real Instagram or user data.
The goal is to isolate structural effects, not predict real-world behavior.

## How to run
1. Run the simulation notebook (Step 4)
2. Save exposure data
3. Visualize results (Step 5)

## What I learned
- How feedback loops emerge in algorithmic systems
- Why causal thinking matters in machine learning
- How small design choices can create large downstream effects

This project was built as an independent learning and research exercise.
