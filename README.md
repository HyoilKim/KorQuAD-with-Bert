### KorQuAD 1.0 with Bert

tensorflow : 1.15.0 (colab gpu 사용을 위해 공식 doc의 1.11.0 사용x) </br>

| hyper parameter | value |
|:--------:|:--------:|
| train_batch_size | 16 |
| learning_rate | 3e-5 |
| num_train_epochs | 2.0 |
| max_seq_length | 256 |
| doc_stride | 128 |

exact_match: 69.70 / f1: 89.6
