# IMDB-review-classification

This repo helps in doing a sentiment analysis for a given movie review. 
<img src='https://www.researchgate.net/profile/Kwan_Hui_Lim/publication/324639092/figure/fig3/AS:634364379545604@1528255662977/Positive-and-negative-emojis-used-for-the-sentiment-analysis.png' width=500/>

## Text Preprocessing
1. Tokenization
2. Texts to Sequences
3. Padding

## Model Structure

|Layer (type)| Output Shape| Param|    
|------------|-------------|------|
|embedding_2 (Embedding)   |   (None, 120, 16)      |     160000    |
flatten_2 (Flatten)     |     (None, 1920)    |          0         |
dense_6 (Dense)         |    (None, 64)        |        122944    |
dense_7 (Dense)        |    (None, 32)          |      2080      |
dense_8 (Dense)         |     (None, 1)         |        33       |


## Tools used
1. Weights and bias [WANDB](https://www.wandb.com/)
2. Embedding projector [data visualization](http://projector.tensorflow.org/)


## TODO:
With the help of tensorflow.js, the trained model can be used to develop a web application. 
