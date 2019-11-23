# Final-Project-Group8

## Installation

**First, install the Chrome browser driver:**

`brew install chromedriver`

**Second, create and activate a Python virtual environment:** 

`python3 -m venv testenv
source testenv/bin/activate
pip3 install -r requirements.txt`

## Data
All of the data for this project can be found on [Google Drive](https://drive.google.com/drive/folders/14YJngXIdbD-_D3qks1_uSd5Pnh2vfCad?usp=sharing). The data utilized comes from the [iMaterialist Challenge (Fashion) at FGVC5](https://github.com/visipedia/imat_fashion_comp) competition on [Kaggle](https://www.kaggle.com/c/imaterialist-challenge-fashion-2018).

## Sources
https://github.com/visipedia/imat_fashion_comp
https://www.kaggle.com/nlecoy/imaterialist-downloader-util

Dealing with multilabel in pytorch
MultiLabelBinarizer
https://www.kaggle.com/anqitu/for-starter-json-to-multilabel-in-24-seconds
https://stackoverflow.com/questions/52855843/multi-label-classification-in-pytorch
https://www.analyticsvidhya.com/blog/2019/04/build-first-multi-label-image-classification-model-python/
https://github.com/utkuozbulak/pytorch-custom-dataset-examples
https://www.kaggle.com/mratsim/starting-kit-for-pytorch-deep-learning

https://homes.cs.washington.edu/~bboots/files/GuerinBMVC18.pdf
https://www.learnopencv.com/pytorch-for-beginners-image-classification-using-pre-trained-models/

https://www.kaggle.com/renatobmlr/pytorch-densenet-as-feature-extractor
https://towardsdatascience.com/simple-implementation-of-densely-connected-convolutional-networks-in-pytorch-3846978f2f36

https://github.com/spotify/annoy
https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.BallTree.html#sklearn.neighbors.BallTree

REMOVED FROM TRAIN UNCOMMON LABELS 161, 162, and 46
This includes images: 

## TO DO
1) Model architecture/tuning - Both (Mary has 2 baseline models)
  a) Run best with image transformations
  
2) For training, plot loss over epochs, class distribution plots - Jessica 😒
  - Baseline, Pretrain (All)

4) Pre-trained models - Both
  a) Resnet50 
  b) Densenet161
  c) MobileNet
  
5) Parameter tables and network diagrams - Both 🤞🏻
6) Presentation - Both
7) Joint report - Both
8) Web App - Both
