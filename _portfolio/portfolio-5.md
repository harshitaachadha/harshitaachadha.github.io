---
title: "End-to-End LSTM Pipeline for Song Generation"
excerpt: "<img src='/images/rr.png'><br/><br/>A Recurrent Neural Network (RNN) based three-stage architecture for end to end music generation."
collection: portfolio
---
> The poster for this project can be found [here](/files/Final Project Poster_Chadha.pdf){:target="_blank"}

> The research article for this project can be found [here](/files/Final Project Report_Chadha.pdf){:target="_blank"}

> The GitHub repository for this project can be found [here](https://github.com/harshitaachadha/Recurrent-Rhapsody){:target="_blank"}

Recurrent Rhapsody is a three-component pipeline made up of three distinct neural networks that when combined result in the production of a novel sequentially dependent application. In the first part, an LSTM model generates lyrics of a song, given a prompt. This song is then fed into the second stage, sentence-BERT embedding and cosine similarity-based algorithm, where a similarity mapping is done to obtain the song with the most similar lyrics to the one generated. The MIDI track for this resultant song is then fed into a neural network model as the priming sequence to generate a new backing track. The lyrics along with this track are then output as the final results of the pipeline ready to be combined.

The entire project was created using Python 3.10.11 and its various libraries. The first component, an LSTM model for text sequence, i.e. lyrics prediction, was built using TensorFlow.keras. The second component used to obtain a complementary priming sequence was built using a pre-trained sentence-BERT model from hugging face interfaced using the sentence tokenizer library. The third component, a Gated Recurrent Unit-based model, was built using PyTorch. The first and second components of the model were trained in the Google Collaboratory environment using the NVIDIA Tesla T4 GPU. The third component was trained using Jupyter on the local machine using a 1.1 GHz Quad-Core Intel Core i5 processor and no dedicated GPU.
