# Machine Learning Engineer Nanodegree
## Capstone Proposal
Rairo Mukamuri
June 5th, 2020


## Proposal
Plant Disease Detection using Pytorch and Fastai

### Domain Background

As Africa grows in population every year the demand for food is also rising, however a growing threat in the form of plant diseases threatens to worsen the already strained food supply on the continent. 

Pest and disease induced crop losses have devasted african farms but thanks to advances in machine learning farmers can detect diseases early through the use of computer vision in the browser or on a mobile device.


### Problem Statement

The goal of this project is to fit a Convolutional Neural Network developed using the Fastai library and Pytorch. I am going to use transfer Learning with ResNet a deep residual learning framework developed at Microsoft in order to achieve accurate classification of the plant images. 

### Datasets and Inputs

The PlantVillage dataset consists of 54303 healthy and unhealthy leaf images divided into 38 categories by species and disease.

The images span 14 crop species: Apple, Blueberry, Cherry, Grape, Orange, Peach, Bell Pepper, Potato, Raspberry, Soybean, Squash, Strawberry, and Tomato. It contains images of 17 fundal diseases, 4 bacterial diseases, 2 mold (oomycete) diseases, 2 viral diseases, and 1 disease caused by a mite. 12 crop species also have images of healthy leaves that are not visibly affected by a disease.

### Solution Statement

The solution will be 

### Benchmark Model

For this problem, the benchmark model will be 

### Evaluation Metrics

Prediction results are evaluated on 

### Project Design

Before even start training models, I will first take glimpse of the data see what the shape and is and how they are formatted. Then I will start doing my natural language processing and extract information such as character counts, sentence length, TF-IDF vector...etc. Since in this case there are not too many features, I don't think PDA feature selection is required. I may perform some graph visualization for better understanding of the data distribution. This dependes on whether I can find such existing implemntation/library or whether I have enough time to do it from scratch. 

For training models, I plan to choose 2-3 different models to compare. Because this is a classification problem, a few approaches in my head would be regrssion, decision trees, SVM, and random forrest. Using cross-validation I can find which model performs best, and then use that one to tweak relative parameters. The final accuracy will be tested against the test data set provided by Kaggle.

### References

- 
- https://arxiv.org/ftp/arxiv/papers/1604/1604.03169.pdf
- https://medium.com/datadriveninvestor/creating-an-ai-app-that-detect-diseases-in-plants-using-facebooks-deep-learning-platform-pytorch-15faaeb6bec3