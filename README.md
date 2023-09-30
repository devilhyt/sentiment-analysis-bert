# Sentiment Analysis based on BERT
This repo provides code from the [基於BERT的文章情感識別](https://medium.com/@devilhyt/bert遷移學習-文章情感識別-daa6521af5c0) article.

## Folder Structure

```
    .
    ├── data                                    # PTT raw data
    │   ├── happy.csv
    │   ├── hate.csv
    │   └── sad.csv
    ├── image                                   # Chart of model training results
    │   ├── accuracy.png
    │   └── loss.png
    ├── ptt_dataset                             # PTT dataset
    │   ├── dataset.csv      
    │   ├── test.csv
    │   ├── train.csv
    │   └── validation.csv
    ├── ptt_spider.py                           # PTT crawler tool
    ├── sentiment-classification-bert.ipynb     # Main program
    ├── visualize.ipynb                         # Visualizing Attention with BertViz
    ├── bert-base-chinese                       # BERT pretrained model
    └── bert-base-chinese-20220610-5            # BERT fine-tuned model
```