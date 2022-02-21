Relationship extraction (RE) is the task of extracting semantic relationships between entities from a document, which can in turn be used to populate a database with relational facts contained in a piece of text. Consider the following two text pieces on two different people. 

```
William Shakespeare was born and raised in Warwickshire. At the age of 18, he married Anne Hathaway, with whom he had three children: Susanna Hall and twins Hamnet Shakespeare and Judith Quiney.
```

RE models can extract triples, which can be represented as edges in a knowledge graph, such as < William Shakespeare, Spouse, Anne Hathaway>. Considering the importance of extracting information in this format, the NLP community has a growing interest in producing datasets capable of training machine learning models to perform RE. However, humans have manually annotated all of these datasets, which makes it difficult to expand RE to different genres and languages. Therefore, in this project we propose Biographical. Biographical is the first and the largest dataset for biographical RE built in a semi-supervised manner with ten relationship categories. We also produce a manually annotated subset that can be used for evaluations.


## Dataset Statistics

|            | normal  | coref   | skip    |
|------------|---------|---------|---------|
| birthdate  | 51,524  | 47,977  | 45,211  |
| birthplace | 50,226  | 46,551  | 17,537  |
| deathdate  | 17,197  | 14,500  | 5,925   |
| deathplace | 18,944  | 20,430  | 10,790  |
| occupation | 18,114  | 18,111  | 8,716   |
| ofParent   | 6,352   | 10,291  | 5,596   |
| educatedAt | 5,639   | 9,415   | 3,858   |
| hasChild   | 2,209   | 4,053   | 2,123   |
| sibling    | 2,083   | 3,601   | 1,997   |
| Other      | 173,969 | 175,916 | 103,248 |
| Total      | 346,257 | 350,845 | 205,001 |





