# Clinical-Question-Answering-Using-BERT

What if we want to support any question a physician might want to ask instead of simpler rule-based questions such as "is a disease present"? To do this, we'll have to use more recent artificial intelligence techniques and large datasets as opposed to mere classification based on tabular data. In this project we go through the pre- and post-processing involved in applying [BERT](https://github.com/google-research/bert) to the problem of question answering. After developing this infrastructure, we use the model to answer questions from clinical notes.

Implementing question answering can take a few steps, even using pretrained models. 
- First retrieve our model and tokenizer (preparing the input), mapping each word to a unique element in the vocabulary and inserting special tokens. 
- Then, the model processes these tokenized inputs to create valuable embeddings and performs tasks such as question answering!

This project is just a "simple" example of what might be ran at production scale!