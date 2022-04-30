## Chinese NER using Bert

BERT for Chinese NER. 

### dataset list

1. cner: datasets/cner



### Cner result


|              | Accuracy (entity)  | Recall (entity)    | F1 score (entity)  |
| ------------ | ------------------ | ------------------ | ------------------ |
| BERT+Softmax | 0.9586(0.9566)     | 0.9644(0.9613)     | 0.9615(0.9590)     |
| BERT+CRF     | 0.9562(0.9539)     | 0.9671(**0.9644**) | 0.9616(0.9591)     |
| BERT+Span    | 0.9604(**0.9620**) | 0.9617(0.9632)     | 0.9611(**0.9626**) |

### CLUENER result


|              | Accuracy (entity)  | Recall (entity)    | F1 score (entity)  |
| ------------ | ------------------ | ------------------ | ------------------ |
| BERT+Softmax | 0.7897     | 0.8031     | 0.7963    |
| BERT+CRF     | 0.7977 | 0.8177 | 0.8076 |
| BERT+Span    | 0.8132 | 0.8092 | 0.8112 |
