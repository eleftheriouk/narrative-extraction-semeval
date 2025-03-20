# Multilingual Narrative Extraction - SemEval 2025 Task 10

Code for my undergrad bachelor's thesis on the SemEval-2025 Task 10. It includes base hierarchical models aligned with the way the problem is structured, along with different training strategies and techniques that build on top of these models and tackle different challenges of the task from different angles.

For more info about this task, see the [official SemEval site](https://propaganda.math.unipd.it/semeval2025task10/).

## Official SemEval Test Results (Updated Leaderboard)

Our primary approach, consisting of an ensembled version of a continual learning training strategy was evaluated across five languages achieving competitive results:

- Portuguese: Ranked 3rd out of 14 teams
- English: Ranked 5th out of 27 teams
- Russian: Ranked 5th out of 15 teams
- Bulgarian: Ranked 5th out of 13 teams
- Hindi: Ranked 5th out of 14 teams
  
A notable aspect of our approach was stability, showing lower variance in predictions compared to similarly ranked systems for certain languages.

The official SemEval leaderboard can be found [here](https://propaganda.math.unipd.it/semeval2025task10/leaderboardv2.html), with my entry under the name "KostasThesis2025".

## Submission Paper

For more details on the approach we followed, please refer to the [paper](./paper.pdf)
