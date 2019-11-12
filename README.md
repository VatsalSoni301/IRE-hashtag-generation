# IRE-Hashtag-Generation

## Introduction

* The problem is to generate the hashtags for a given multi-modal post that could be a text or an image. The generated hashtags should be relevant to the existing hashtags that may present along with the post.

## Prerequisites
* python3
* pandas
* numpy
* nltk
* word2vec
* glove
* gensim

## Dataset used
```
https://drive.google.com/drive/u/2/folders/1IakHwyTgaTKxZa0RqQ99TRuamhEi-8xp
```

## Code

### Training Text-Model

#### All different models have been kept in different files.

* baseline.ipynb :- This file contains baseline model
* generate_hashtags_from_text_all.ipynb :- This file contains global model trained on a complete corpus (including all 8 topics)
* generate_hashtags_from_text_multiple.ipynb :- This file contains word2vec and glove model that is trained for each topic.
* generate_hashtags_from_text.ipynb :- This file contains word2vec and glove model trained only on travel topic
* generate_top_hashtags.ipynb :- This file contains code to generate topic wise top-100 hashtags from a corpus.
* train_on_top.ipynb :- This file contains word2vec model merged with pre trained wikipedia glove embedding to predict hashtags.

### Testing Text-Model

#### Use following files to test different models and measure accuracy.

* test_text.ipynb :- This file contains code to evaluate word2vec model and measure the accuracy.
* test_text_glove.ipynb :- This file contains code to evaluate glove model and measure the accuracy.
* test_text_global.ipynb :- This file contains code to evaluate global word2vec model and measure the accuracy.

## Links
* Web page link
    * ``` https://rebrand.ly/ire-hashtag-generation ```
* YouTube video link
    * ``` https://rebrand.ly/ire-hashtags-generation-video ```