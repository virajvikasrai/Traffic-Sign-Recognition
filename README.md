# Traffic-Sign-Recognition
Convolutional Neural Network model to classify 43 categories of traffic sign.
## Importing Dataset
Imported the dataset from the machine. Extracted the class of the image using the image path. Resized the image and dumped it in a list and dumped their class number in another ist in the same order.
## Data Visualization
Ploted a count plot to understand the distribution of images pertaining to different classes. Although there's an imbalance none of the class are under-represented enought to trouble the algorithm.
Plotted 25 random pictures for self satisfaction :D
## Input normalization
## Data Preparation
Splitted the dataset into train and validation set. This is an important step in this case to evaluate the model as we dont have an already labelled test set to do the same. (The dataset belongs to German Traffic Recognition Benchmark 2011 - competition and hence test set is not labelled).
One hot encoding the labels. (required by the softmax later-on)
## Data Augmentaion
We must be carefull as CNN's can overfit easily and might not perform well on validation and test set. Augmenting the data is one of the way to do so. Here I'll use keras image-data-generator.
## Building Model.
## Plotting Accuracy and Loss.
Verifies model performance.
