# Hate-Speech-Analysis-using-Neural-networks
CSE 6240 - Web Search &amp; Text Mining Project - Spring 2020

### Preprocessing:
  - Run the "Preprocessing.ipynb" to preprocess the data.

### Data Analysis:
1. Sentiment Analysis
  - Navigate to vaderSentiment folder. Place the input file in the Input folder and run "sentiment.py"
2. Ngrams:
  - Run the python notebook "Preprocessing.ipynb" to preprocess and generate n-grams from the data
3. Hashtag Correlation:
  - Run the code "Hashtags association.py" for generating correlation between hashtags.
4. T-SNE plot:
  - Run the code WordTSNE.ipynb to get the TSNE-Plots
5. K-Means Clustering:
  - Run the code Tweet_cluster.ipynb to generate the K-Means Cluster


## Dataset.
We are using the dataset prepared by crowd-sourcing after an 8 month study from the paper, "Twitter Abusive Behavior identification".
The dataset can be downloaded from https://www.dropbox.com/sh/4mapojr85a6sc76/AABYMkjLVG-HhueAgd0qM9kwa?dl=0

## Steps to run the code
1) Download the CSV and configure the path.

2) Download the notebooks and run the notebooks on Google Colab. Change the runtime configuration to TPU.
 
  2.1) For BERT + KimCNN
  run the code BERT_KimCNN.ipnyb
  
  2.2) For BERT + CNN
  run the code BERT_CNN.ipnyb
  
  2.3) For BERT + LSTM
  run the code BERT_LSTM.ipnyb

3) The hyperparameters have been hardcoded and can be modified accordingly.

