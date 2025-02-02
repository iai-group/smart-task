# smart-task
[IAI](http://iai.group) participation at Semantic Answer Type Prediction task at ISWC 2020 [https://smart-task.github.io/](https://smart-task.github.io/)

# Code
 - Coming soon!
# Results
## Runs on the training and test data of the task can be found in [results](results) folder
## Evaluation results for Category classification

| Method   |      DataSet      |  Train Accuracy | Test Accuracy |
|----------|:-------------:|------:|------:|
| SVM |  DBPedia | 0.958 |  0.964 |
| BERT |    DBPEdia   |  0.970 |0.977 |
| SVM | Wikidata |    0.956 |0.96 | 
| BERT | Wikidata |    0.964 | 0.97 |

## Evaluation results for Resource Type classification  (DBPedia)

| Method   | Train NDCG@5 | Train NDCG@10 | Test  NDCG@5 | Test NDCG@10 |
|----------|------:|------:|------:|------:|
| SVM-XBERT  | 0.773 | 0.744 | 0.790 | 0.778 | 
| BERT-XBERT  | 0.776 | 0.747 |  0.804 | 0.793 |
| BERT-IR Type-centric (BM25)  | 0.492 | 0.509 | | |
| BERT-IR Type-centric (LM)  | 0.526 | 0.541 | | | 
| BERT-IR Entity-centric (BM25, k=20)  | 0.483 | 0.503 | | |
| BERT-IR Entity-centric (BM25, k=50)  | 0.448 | 0.474 | | |
| BERT-IR Entity-centric (BM25, k=100)  | 0.423 | 0.444 | | |


## Evaluation results for Resource Type classification  (Wikidata)
| Method   |  Train MRR | Test MRR | 
|----------|------:|------:|
| SVM-XBERT  |  0.66  | 0.67|
| BERT-XBERT  |  0.67  | 0.67|

