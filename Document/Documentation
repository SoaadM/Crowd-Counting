# Self Driving Car Object Detection

## Abstract
We all know self-driving cars is one of the hottest areas of research and business for the tech giants. What seemed like a science-fiction, a few years ago, now seems more like something which is soon to become a part and parcel of life. The reason, I am saying “soon to be” is because of the fact that even though companies like Tesla, Nissan, Cadillac do have self-driving car assistance software, but, they still require a human to keep an eye on the road and take control when needed. However, it is fascinating to see how far we have come in terms of innovation and how fast technology is advancing. So much so, that now, with the help of basic deep learning, neural network magic...

## Design 
This project is one of the T5-Batch 3 Data Science sadaya BootCamp requirements ,The dataset was sourced from Roboflow , The Roboflow Model Library contains pre-configured model architectures for easily training computer vision models Deep Learning has revolutionized Computer Vision, and it is the core technology behind capabilities of a self- driving car. Convolutional Neural Networks (CNNs) are at the heart of this deep learning revolution for improving the task of object detection. A number of successful object detection systems have been proposed in recent years that are based on CNNs. In this paper, an empirical evaluation of three recent meta-architectures: SSD (Single Shot multi- box Detector), R-CNN (Region-based CNN) and R-FCN (Region-based Fully Convolutional Networks) was conducted to measure how fast and accurate they are in identifying objects on the road, such as vehicles, pedestrians, traffic lights, etc. under four different driving conditions: day, night, rainy and snowy for four different image widths: 150, 300, 450 and 600. The results show that region- based algorithms have higher accuracy with lower inference times for all driving conditions and image sizes. The second principle contribution of this paper is to show that Transfer Learning can be an effective paradigm in improving the performance of these pre-trained networks. With Transfer Learning, we were able to improve the accuracy for rainy and night conditions and achieve less than 2 seconds per image inference time for all conditions, which outperformed the pre-trained networks.

## Data
The dataset contains 97,942 labels across 11 classes and 15,000 images. There are 1,720 null examples (images with no labels) and eighth columns (Filename, width, height, class, xmin, ymin, xmax, ymax)
All images are 1920x1200 (download size ~3.1 GB). We have also provided a version down sampled to 512x512 (download size ~580 MB) that is suitable for most common machine learning models

## Algorithm
* Data manipulation and cleaning
    * Applied feature Selection by dropping unnecessary columns.
    * Applied feature reduction due to computational limitations and selected 100 stratified images out of 15000 images.

* After applying the previous steps to prepare the dataset, we end up with:
   * Images for Training.
   * Images for Validation.
   * Images for Testing.

* To train our detector we take the following steps:
   * Install YOLOv5 dependencies
   * Download custom YOLOv5 object detection data
   * Write our YOLOv5 Training configuration
   * Run YOLOv5 training
   * Evaluate YOLOv5 performance
   * Visualize YOLOv5 training data
   * Run YOLOv5 inference on test images
   * Export saved YOLOv5 weights for future inference

* The YOLO network consists of three main pieces:
   * Backbone - A convolutional neural network that aggregates and forms image features at different granularities.
   * Neck - A series of layers to mix and combine image features to pass them forward to prediction.
   * Head - Consumes features from the neck and takes box and class prediction steps.
   ![alt text](../Images/yolov5_algorithm.png "yolov5 algorithm")

## Model Evaluation and Selection
Since we are dealing with image classification the best course of action is to use convolutional neural networks since it’s very effective in reducing the number of parameters without losing on the quality of models. Images have high dimensionality (as each pixel is considered as a feature). YOLO algorithm employs convolutional neural networks (CNN) to detect objects in real-time. As the name suggests, the algorithm requires only a single forward propagation through a neural network to detect objects. This means that prediction in the entire image is done in a single algorithm run

![alt text](../Images/test1.png)
---
![alt text](../Images/test2.png)
---
![alt text](../Images/test3.png)
---
> [Video demonstration](https://www.youtube.com/watch?v=qaCLV4Y_H3M)

## Tools
* Colab : mostly used to handle GPU intensive tasks
* Pandas: Data Cleaning and manipulation
* NumPy: Mathematical operations
* TensorFlow: Deep Learning
* Seaborn: Data Visualization
* Sklera: Testing the results
