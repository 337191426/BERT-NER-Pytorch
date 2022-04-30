## Chinese NER using Bert

BERT for Chinese NER. 

### dataset list

1. cner: datasets/cner



### Cner result

The overall performance of BERT on **dev(test)**:

|              | Accuracy (entity)  | Recall (entity)    | F1 score (entity)  |
| ------------ | ------------------ | ------------------ | ------------------ |
| BERT+Softmax | 0.9586(0.9566)     | 0.9644(0.9613)     | 0.9615(0.9590)     |
| BERT+CRF     | 0.9562(0.9539)     | 0.9671(**0.9644**) | 0.9616(0.9591)     |
| BERT+Span    | 0.9604(**0.9620**) | 0.9617(0.9632)     | 0.9611(**0.9626**) |

