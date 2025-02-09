# Waste classification using CNN model

## What is a CNN
A CNN model is a type of deep learning algorithm that analyzes and learns features from large amounts of data

## How Do CNNs Work?
Convolutional neural networks work by ingesting and processing large amounts of data in a grid format and then extracting important granular features for classification and detection. Each layer serves a different purpose, performs a task on ingested data, and learns increasing amounts of complexity.

## Architecture of CNN
 CNNs typically consist of three types of layers: a convolutional layer, a pooling layer, and a fully connected layer.
 ![image alt](https://github.com/khrishwanth/Waste_classification/blob/1c0c6512b56f7f21ae9cba15763150404869cf87/images%20(13).jpeg)

 ## Working of CNN model
 To better understand how CNNs work, let’s look at an example
 let’s assume the input data is a set of millions of images of cars.

 
### Convolutional layers 
It apply filters to the input data and learn feature detections. Typically, there are multiple convolutional layers connected via pooling layers. The early convolutional layers extract general or low-level features, such as lines and edges, while the later layers learn finer details or high-level features, such as car headlights or tires.
### Pooling layers 
It decrease the size of the convolutional feature map to reduce the computational costs.
### Fully connected layers 
It learn global patterns based on the high-level features output from the convolutional and pooling layers and generate the global patterns for cars. Once the input data is passed through the fully connected layer, the final layer activates the model, and the neural network issues its predictions.
