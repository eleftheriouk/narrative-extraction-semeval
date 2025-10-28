## SemEval 2025 Task 10: Multilingual Narrative Extraction

A repository documenting the complete development process of our entry at SemEval-2025 Task 10 Subtask 2.

Notebooks contain the process of cleaning and handling very long articles to establishing initial baselines models and then moving to multi-head multi-task hierarchical models. 

Both baseline and hierarchical models revealed serious instability issues. We established different training strategies to overcome this problem. Specifically one of those training strategies is inspired by [Continual or Incremental Learning](https://en.wikipedia.org/wiki/Incremental_learning), which for us that means, our model learns patterns from a specific language before shifting to another language during training phase. We found very interesting insights out of this, with certain language orders strongly affecting model performance compared to others.

For more info about this task, see the [official SemEval site](https://propaganda.math.unipd.it/semeval2025task10/).

### Results
The official SemEval leaderboard can be found [here](https://propaganda.math.unipd.it/semeval2025task10/leaderboardv2.html), with our entry under the name "KostasThesis2025".

### SemEval 2025 Workshop Paper
[Paper](https://aclanthology.org/2025.semeval-1.122/) accepted at ACL 2025 Workshop. 

For more details on the approach we followed, please refer to the [complete thesis paper](./BSc_Thesis_Paper.pdf)

### Cite
If you use this work, please cite it as:

```bibtex
@inproceedings{eleftheriou-etal-2025-kostasthesis2025,
    title = "{K}ostas{T}hesis2025 at {S}em{E}val-2025 Task 10 Subtask 2: A Continual Learning Approach to Propaganda Analysis in Online News",
    author = "Eleftheriou, Konstantinos  and
      Louridas, Panos  and
      Pavlopoulos, John",
    editor = "Rosenthal, Sara  and
      Ros{\'a}, Aiala  and
      Ghosh, Debanjan  and
      Zampieri, Marcos",
    booktitle = "Proceedings of the 19th International Workshop on Semantic Evaluation (SemEval-2025)",
    month = jul,
    year = "2025",
    address = "Vienna, Austria",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.semeval-1.122/",
    pages = "899--908",
    ISBN = "979-8-89176-273-2",
    abstract = "In response to the growing challenge of propagandistic presence through online media in online news, the increasing need for automated systems that are able to identify and classify narrative structures in multiple languages is evident. We present our approach to the SemEval-2025 Task 10 Subtask 2, focusing on the challenge of hierarchical multi-label, multi-class classification in multilingual news articles. We present methods to handle long articles with respect to how they are naturally structured in the dataset, propose a hierarchical classification neural network model with respect to the taxonomy, and a continual learning training approach that leverages cross-lingual knowledge transfer."
