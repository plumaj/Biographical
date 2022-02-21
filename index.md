Relationship extraction (RE) is the task of extracting semantic relationships between entities from a document, which can in turn be used to populate a database with relational facts contained in a piece of text. Consider the following two text pieces on two different people. 

```
William Shakespeare was born and raised in Warwickshire. At the age of 18, he married Anne Hathaway, with whom he had three children: Susanna Hall and twins Hamnet Shakespeare and Judith Quiney.
```

```
Henry Baynton (23 September 1892 in Warwickshire – 2 January 1951 in London) was a British Shakespearean actor of the early 20th century.
```

RE models can extract triples, which can be represented as edges in a knowledge graph, such as < William Shakespeare, Spouse, Anne Hathaway>. Considering the importance of this, the NLP community has a growing interest in producing datasets capable of training machine learning models to perform RE. However, humans have manually annotated all of these datasets, which makes it difficult to expand RE to different genres and languages. Therefore, in this project we propose Biographical. Biographical is the first and the largest dataset for biographical RE built in a semi-supervised manner with ten relationship categories. We also produce a manually annotated subset that can be used for evaluations.




