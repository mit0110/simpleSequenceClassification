# Simple Sequence Labeling

This repository contains sample code in Keras for a (CNN|BiLSTM)-BiLSTM-CRF for sequence labeling tasks. It has being developed for a tutorial and its objetive is purely educational.

## Data

The [original dataset](https://www.kaggle.com/gagandeep16/ner-using-bidirectional-lstm) was uploaded to Kaggle, along with a vanilla LSTM implementation. We have also hosted it into the UNC servers:

* [Full dataset](https://cs.famaf.unc.edu.ar/~mteruel/datasets/tensorflowMeetup/ner.csv) (150M)
* [Sample dataset](https://cs.famaf.unc.edu.ar/~mteruel/datasets/tensorflowMeetup/ner.sample.csv) (14M)


## Requirements

To run the network, we recommend you to use python 3.5 and install

* Keras 2.1.5
* scikit-learn 0.19.1
* pandas 0.23.0
* seaborn

