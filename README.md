Description
=============
#### - BERT (Bidirectional Encoder Representation of Transformer) fine-tune
  
  <img src="https://user-images.githubusercontent.com/52263269/98573579-5c431280-22fa-11eb-8504-381f52b7b29f.png" width="90%"></img>
  
  - What is BERT? https://blog.naver.com/qbxlvnf11/222140142456

#### - DistilBERT
  - The Distilling Knowledge method is applied to the existing BERT model
  - Similar performance while having a much smaller size and faster speed
  - Distilling Knowledge method
  
  <img src="https://user-images.githubusercontent.com/52263269/200163187-38c7f804-18f1-4062-b59e-23ff2c8d5010.png" width="90%"></img>  

#### - Upload code as a Jupiter Notebook file (.ipynb) for immediate understanding


Contents
=============

#### - Fine-tuning of BERT for text classification
  - [BERT implementation with pytorch-pretrained-BERT library](https://github.com/qbxlvnf11/BERT-series/blob/master/pytorch_pretrained_BERT.ipynb)
  - [BERT implementation with keras ktrain library](https://github.com/qbxlvnf11/BERT-series/blob/master/ktrain_BERT.ipynb)
  - [DistilBERT implementation with huggingface transformers library](https://github.com/qbxlvnf11/BERT-series/blob/master/huggingface_DistilBERT.ipynb)

Datasets
=============

#### - News Aggregater

https://www.kaggle.com/uciml/news-aggregator-dataset

#### - Detecting Insults in Social Commentary

https://www.kaggle.com/c/detecting-insults-in-social-commentary

#### - Disaster Tweets

https://www.kaggle.com/competitions/nlp-getting-started/data?select=train.csv

References
=============

#### - Papers

```
@article{BERT,
  title={BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding},
  author={Jacob Devlin, Ming-Wei Chang, Kenton Lee, Kristina Toutanova},
  journal = {arXiv},
  year={2018}
}
```

```
@article{DistilBERT,
  title={DistilBERT, a distilled version of BERT: smaller, faster, cheaper and lighter},
  author={Victor Sanh, Lysandre Debut, Julien Chaumond, Thomas Wolf},
  journal = {arXiv},
  year={2019}
}
```

#### - ktrain

https://towardsdatascience.com/bert-text-classification-in-3-lines-of-code-using-keras-264db7e7a358

https://github.com/amaiya/ktrain/blob/master/examples/text/IMDb-BERT.ipynb

#### - pytorch-pretrained-BERT

https://pypi.org/project/pytorch-pretrained-bert/

https://github.com/shudima/notebooks

#### - huggingface transformers BERT

https://github.com/huggingface/transformers

https://www.kaggle.com/code/donkeys/distilbert-xlnet-with-tf-and-huggingface/notebook

Erratum of Jupyter Notebook Files
=============

#### - pytorch_pretrained_BERT.ipynb

- [66] block: train_loss -> loss

#### - ktrain_BERT.ipynb

- [4] block: changing name of X axis and Y axis of plot

Author
=============

#### - LinkedIn: https://www.linkedin.com/in/taeyong-kong-016bb2154

#### - Blog URL: https://blog.naver.com/qbxlvnf11

#### - Email: qbxlvnf11@google.com, qbxlvnf11@naver.com
