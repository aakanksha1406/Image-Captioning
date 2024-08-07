# Image Caption Generator - Flickr Dataset
**Environment:** Kaggle

## Project Information

The objective of the project is to predict the captions for the input image. The dataset consists of 8k images and 5 captions for each image. The features are extracted from both the image and the text captions for input. The features will be concatenated to predict the next word of the caption. CNN is used for image and LSTM is used for text. BLEU Score is used as a metric to evaluate the performance of the trained model.




## Libraries

- numpy
- matplotlib
- keras
- tensorflow
- nltk

## Neural Network

- VGG16 Network
- CNN-LSTM Network
  
**BLEU-1 Score:** 0.562578
**BLEU-2 Score:** 0.374006
