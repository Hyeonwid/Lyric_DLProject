# Lyric_DLProject
## Authors
David Qian and Carl Widmann

## Introduction
The lyric project is a natural language processing problem where a model takes in lyrics from a certain artist and generates lyrics based on processed data about the artists past songs. Natural language processing is a deep learning model that can take in text, analyze the input, and generate new possible text.

## Abstract

We begin by importing Beatles lyrics. Then, we index each word that shows up into an dictionary with words and their corresponding integers. Then we turn each lyric into sequences and convert the sequences into trainable data. We then pad the data in order to create data that is of the same length. We then split the data into the training, valid, and test data. We then standardize the data with the standard deviation and mean. 

### Training and Evaluation

We loaded in a pretrained tokenizer and the gpt2 base model. We tokenized the dataset using special tokens and split the training data. We trained four epochs with batch size of four to optimize resulting training time and accuracy. We have a BERT score precision of 78% on average and a relatively low perplexity of 5.34. We uploaded our final version notebook called FinalCarlDavidLyricPrj with the updated code. 

<!-- ![plot](./dl.png) -->


## Datasets

In this project, the researcher works with a lyrics dataset, in this case, the Beatles lyrics dataset. The dataset contains songs written by the Beatles and is used to train a language model, specifically a GPT-2 model, to generate lyrics in the style of the Beatles.


## Results and Discussions

The strength of this approach is that it leverages the capabilities of the GPT-2 model, which is a powerful language model that has been pre-trained on a vast amount of text. This allows the model to generate reasonably coherent and grammatically correct sentences.
However, there are some limitations and potential areas for improvement. One limitation is that the model may generate text that is grammatically correct and similar in style to the Beatles' lyrics but doesn't make sense or is irrelevant.
Furthermore, while the model might mimic the style of the Beatles, capturing the depth, creativity, and nuances of their lyrics is a far more challenging task. Finally, the quality of the generated lyrics would likely improve with a larger and more diverse training dataset.

