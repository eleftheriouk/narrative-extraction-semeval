## SemEval 2025 Task 10: Multilingual Narrative Extraction

A repository documenting the complete development process of our entry at SemEval-2025 Task 10 Subtask 2.

Notebooks contain the process of cleaning and handling very long articles to establishing initial baselines models and then moving to multi-head multi-task hierarchical models. 

Both baseline and hierarchical models revealed serious instability issues. We established different training strategies to overcome this problem. Specifically one of those training strategies is inspired by [Continual or Incremental Learning](https://en.wikipedia.org/wiki/Incremental_learning), which for us that means, our model learns patterns from a specific language before shifting to another language during training phase. We found very interesting insights out of this, with certain language orders strongly affecting model performance compared to others.

For more info about this task, see the [official SemEval site](https://propaganda.math.unipd.it/semeval2025task10/).

### Results
The official SemEval leaderboard can be found [here](https://propaganda.math.unipd.it/semeval2025task10/leaderboardv2.html), with our entry under the name "KostasThesis2025".

### SemEval 2025 Workshop Paper
[Paper](./SemEval_Submission_Paper.pdf) accepted at ACL 2025 Workshop. 

### Full Thesis
For more details on the approach we followed, please refer to the [complete thesis paper](./BSc_Thesis_Paper.pdf)
