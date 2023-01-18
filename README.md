## In this folder, I compiled a number of my example projects that involve various regression, classification, and deep learning algorithms.



##   Risk Analysis:
   This project has the following purposes: 1. Evaluating the risk involved with an event. 2. Performing classification and predicting class labels based on risks and other factors. 3. Exploring metrics and methods towards accurate risk management. Data wrangling includes label encoding, log transformation, data balancing, and scaling. Predictions by LGR, Linear Discriminant Analysis, KNN, CART, NB, RF, SVM, XGBM, and LGBM are compared.

##   Optimization and regression:
   The notebook titled "Photovoltaic" addresses solar power prediction. This analysis provides insights on renewable energy usage and maintenance, which are becoming more and more relevant in the age of electrical cars and global warming awareness.


## Natural Language Processing (NLP):
### 1. ARXIV abstract Clustering
   Unsupervised learning is important for clustering and mining scientific literatures. ARXIV from Cornell University is a collection of over 2 million open scientific papers. K-means, t-SNE and UMAP are used to perform interactive clustering based on abstracts of ARXIV literatures, to complement some other open-source scientific literature mining tools such as Carrot2 and to provide large-scale scientific literature study and topic trend research.
### 2. Twitter:
   A NLP project to classify texts (in this case, tweeters) depending upon its likelihood of being about a real disaster. Data cleaning follows: a. raw text corpus -> b. processed text -> c. tokenized text -> d. corpus vocabulary -> e. text representation. Matrix factorization based GLoVe embeddings are used before feeding into a simple LSTM, a dual-LSTM, and a BERT model with variable learning rate, batch size, dense layer, dropout layer, and epoch.

## Computer vision (CV):
### 1. U-net for segmentation: 
   Tuning a U-net architecture to perform semantic segmentation for self-driving cars. Results are evaluated by training/validation accuracy, training/validation loss, as well as Recall, Precision, Specificity, IoU, TDR, F1-Score of each individual class.
### 2. Object detect: 
   Using a pretrained Detectron 2 for instance segmentation, panoptic, and keypoint monitoring, along with YOLO (You Only Look Once) detection. YOLO v3 preprocessing includes getting configuration and weights, setting minimum probability to eliminate weak predictions, preview 2D image input, returning 4D blob after mean substraction, normalization, and RB channel swapping, forward pass the blob to the network, as well as configuring colors, bounding boxes, confidences and threshold for a list of predicted class labels.


##  Time series: 
   Time series analysis aims to analyze the correlation between time and any time-dependent variables. In the notebooks titled "Project T" and "Project T2", the sample data are imported from YFinance API and elsewhere. LSTM with different optimizers and parameters are able to make predictions with reasonably good scores, along with other time seriels models. One of the notebook uses Keras, and the other uses Tensorflow.
   
## Olist Customer Analysis
   Olist is a Brazilian ecommerce platform. Seller, customer, order, and product information are provided by Olist and used to predict customer satisfaction, which can be critical to the growth and success of any ecommerce platforms. Many of the original features did not correlate well with the target (class label 1 for satisfaction). Instead, the frequency of purchase by the same customer, seller popularity, time differences between purchasing stages, delivery speed, regional population and income are engineered as new features. Along with features such as product description length, product categories, seller state etc., these newly engineered features lead to much enhanced AUC-ROC scores of over 0.85. Logistic Regression and Random Forest Classifier generate satisfying F1 scores with 100k rows and 15 features. XGboost can bring the AUC-ROC and F1 score slightly higher with proper hyperparameter tuning. Time lapse videos of sales map are produced by using the Python Folium library. Recency, Frequency, and Monetary (RFM) analysis is used to perform customer segmentation with individualized customer relationship management (CRM) strategies.
