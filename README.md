## In this folder, I compiled a number of my example projects that involve various regression, classification, and deep learning algorithms.



##   Risk Analysis:
This project has the following purposes: 1. Evaluating the risk involved with an event. 2. Performing classification and predicting class labels based on risks and other factors. 3. Exploring metrics and methods towards accurate risk management. Data wrangling includes label encoding, log transformation, data balancing, and scaling. Predictions by LGR, Linear Discriminant Analysis, KNN, CART, NB, RF, SVM, XGBM, and LGBM are compared.

##   Photovoltaic:
A project for solar power prediction. This analysis provides insights on renewable energy usage and maintenance, which are becoming more and more relevant in the age of electrical cars and global warming awareness.


## Twitter:
A NLP project to classify tweeters depending upon its likelihood of being about a real disaster. Data cleaning follows: a. raw text corpus -> b. processing text -> c. tokenized text -> d. corpus vocabulary -> e. text representation. Matrix factorization based GLoVe embeddings are used before feeding into a simple LSTM, a dual-LSTM, and a BERT model with variable learning rate, batch size, dense layer, dropout layer, and epoch.

## Computer vision:
### 1. U-net for segmentation: 
   Tuning a U-net architecture to perform semantic segmentation for self-driving cars. Results are evaluated by training/validation accuracy, training/validation loss, as well as Recall, Precision, Specificity, IoU, TDR, F1-Score of each individual class.
### 2. Object detect: 
   Using a pretrained Detectron 2 for instance segmentation, panoptic, and keypoint monitoring, along with YOLO (You Only Look Once) detection. YOLO v3 preprocessing includes getting configuration and weights, setting minimum probability to eliminate weak predictions, preview 2D image input, returning 4D blob after mean substraction, normalization, and RB channel swapping, forward pass the blob to the network, as well as configuring colors, bounding boxes, confidences and threshold for a list of predicted class labels.


##  Time series (Project T and T2): 
A time series project that aims to analyze the correlation between time and any time-dependent variables. Data are imported from YFinance API or elsewhere. LSTM with different optimizers and parameters are able to make predictions with reasonably good scores, along with some other time seriels models. One of the notebook uses Keras, and the other uses Tensorflow.
