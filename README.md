# Deep-Learning-Project-Work
## Overview
In this repository there is the implementation of Deep Learning Project Work for the Artificial Intelligence Course, carried out as an individual work at the University of Bologna by Riccardo Romeo during AY 2024-25.

The project consists in a Speech-Classification-Task performed using different Deep Learning approaches depending on the type of input data.


## Description
The Project consists in classify a datasets of short speech commands on 30 different classes. In particular, two types of audio representations as been used: the Mel-frequency cepstral coefficients (MFCCs) and the embeddings produced using a Famous Speech Foundation Model: [Wav2Vec2](https://huggingface.co/docs/transformers/model_doc/wav2vec2).

### MFCCs Classification
In this case a Convolutional Model is presented in the form of an "Addition Study", showing the justifications behing each model component. Then, the presented CNN model is compared with VGG16.

### Wav2Vec2 embeddings Classification
In this second main section three different approaches are shown to build downstream classifiers:
1. The first is a Convolutional Model based on 1-D convolutions;
2. The second is a Long-Short-Term Memory model;
3. The third is a Bidirectional Long-Short-Term Memory model.

## Data
 The audio data is open source and it is downloadable from Kaggle. In particular, the data of the [TensorFlow Speech Recognition Challenge](https://www.kaggle.com/competitions/tensorflow-speech-recognition-challenge) has been used.


## Projectual Details
The entire project has been implemented on Google Colab.

## Authors
  - [Riccardo Romeo](https://github.com/RiccardoRomeo01) 
