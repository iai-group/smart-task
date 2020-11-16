# smart-task
Semantic Answer Type Prediction task at ISWC 2020

# Results on the training and test data of the task
## Evaluation results for Category classification

| Method   |      DataSet      |  Train Accuracy | Test Accuracy |
|----------|:-------------:|------:|------:|
| SVM |  DBPedia | 0.958 |  0.964 |
| BERT |    DBPEdia   |  0.970 |0.977 |
| SVM | Wikidata |    0.956 |0.96 | 
| BERT | Wikidata |    0.964 | 0.97 |

## Evaluation results for Resource Type classification  (DBPedia)

| Method   |      DataSet      |  NDCG@5 | NDCG@10 |
|----------|:-------------:|------:|------:|
| SVM-XBERT |  DBPedia | 0.773 | 0.744 | 
| BERT-XBERT |  DBPedia | 0.776 | 0.747 |
| BERT-IR Type-centric (BM25) | DBpedia | 0.492 | 0.509 |
| BERT-IR Type-centric (LM) | DBpedia | 0.526 | 0.541 |
| BERT-IR Entity-centric (BM25, k=20) | DBpedia | 0.483 | 0.503 |
| BERT-IR Entity-centric (BM25, k=50) | DBpedia | 0.448 | 0.474 |
| BERT-IR Entity-centric (BM25, k=100) | DBpedia | 0.423 | 0.444 |


## Evaluation results for Resource Type classification  (Wikidata)
| Method   |      DataSet      |  MRR |
|----------|:-------------:|------:|
| SVM-XBERT | Wikidata |  0.66  |
| BERT-XBERT | Wikidata |  0.67  |


# Results on Test data from the task
## Evaluation results for Category classification

| Method   |      DataSet      |  Accuracy |
|----------|:-------------:|------:|
| SVM |  DBPedia | 0.964 |
| BERT |    DBPEdia   |  0.977 |
| SVM | Wikidata |    0.96 |
| BERT | Wikidata |    0.97 |

## Evaluation results for Resource Type classification  (DBPedia)

| Method   |      DataSet      |  NDCG@5 | NDCG@10 |
|----------|:-------------:|------:|------:|
| SVM-XBERT |  DBPedia | 0.790 | 0.778 | 
| BERT-XBERT |  DBPedia | 0.804 | 0.793 |
| SVM-XBERT |  DBPedia (with short abstracts as question) | 0.566 | 0.596 | 
| BERT-XBERT |  DBPedia (with short abstracts as question) | 0.571 | 0.581 |

## Evaluation results for Resource Type classification  (Wikidata)
| Method   |      DataSet      |  MRR |
|----------|:-------------:|------:|
| SVM-XBERT | Wikidata |    0.67|
| BERT-XBERT | Wikidata |    0.68 |
