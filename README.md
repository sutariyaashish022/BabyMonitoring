# Baby Monitoring
## 1. Title: Robo-Nanny: ConvNets for Intelligent Baby Monitoring

 

### Author: Lily Cheng

 

URL: [http://cs231n.stanford.edu/reports/2017/pdfs/13.pdf](http://cs231n.stanford.edu/reports/2017/pdfs/13.pdf)

 

### Synopsis:

In this paper they have applied supervised learning techniques on state-of-the-art deep convolutional neural networks (CNN) to infer a baby’s status inside a crib using a baby monitor video feed. A dataset of 2500 images assigned to 5 predefined classes was used for training and hyperparameter tuning. After comparing different model architectures, the best class-weighted accuracy of 96.7% on test set was achieved on pre-trained ResNet18.

A Nest IP Camera was placed over a baby crib and a continuous stream of frames were captured at a rate of 1 frame per 10 seconds. Two techniques were briefly tested in order to efficiently extract salient images from the video feed: image subtractions. Optical Flow.

This are few steps for image processing and getting position of baby.

The image subtraction method was selected due to the combination of efficacy and simplicity. The salient images extracted represent 5% of the total raw frames captured.
Manually classify into 5 classes: Caretaker, Empty Crib, Sitting Up, Lying Down Standing Up
Split into Train, Validation and Test Sets.
Resize and Crop images.
 

### Use:

This research can become very useful to create baby monitoring system. By using their technique to detect baby’s position we can get idea about share information threw application. By using opancv we will able to achieve this task and implement baby monitoring system.

## 2. Title: A Study of Vision based Human Motion Recognition and Analysis

### Author: Geetanjali Vinayak Kale, Varsha Hemant Patil

URL: [https://arxiv.org/pdf/1608.06761.pdf](https://arxiv.org/pdf/1608.06761.pdf)

 

### Synopsis:

This paper discusses applications, general framework of human motion recognition, and the details of each of its components. The paper emphasizes on human motion representation and the recognition methods along with their advantages and disadvantages.

The humanoid Body Model uses structural representation and represents a person using his/her joint positions as a set of 2-D (X, Y) or 3-D (X, Y, Z) points in space. The modelling of a stick figure uses human body parts as an estimation methodology. It helps to extract the joint positions of a person from image frame.

Human motion can be determined by taking difference between two-pixel values in consecutive frames. Kinematic approach represents motion trajectory by 2-D trajectory points ( , X Y, ) T or 3-D trajectory points( , X Y, , Z T). Each point corresponds to respective joint value in frame for human posture. Image or shape approach represents motion using optical flow or using MHI or MEI. Human motion can be either directly recognized from image sequences, or it can be done in a multiple layer process. Generally, for simple actions, motion is recognized directly from image sequences and they can be viewed as single layer approaches.

           

 

### Use:

For baby monitoring system we will using computer vision to detect activity or motion of baby. So basically, detect baby motion is similar to human motion detection. By using this research, we will get idea about different data set and different method to detect human activity and detection.

After this we will create personalized data sate from human motion which we can relate with baby monitoring. And by Appling this we can get idea about activity of baby and we can alert parents threw application if something dangerous like baby fall and crying etc.

 

 

## 3.Title: Moving object detection and tracking using deep learning neural network and correlation filter

 

### Author: H S G Supreeth ; Chandrashekar M Patil

 

URL: [https://ieeexplore.ieee.org/document/8473354](https://ieeexplore.ieee.org/document/8473354)

 

 

### Synopsis:

The object detection is the first step in videos before performing the complicated tasks such as tracking. The paper mainly focuses on two algorithms:

The Gaussian mixture model (GMM) for object detection and correlation filters are used for object tracking. This correlation algorithm is mainly designed to detect the cars and humans while the performance is analyzed with True Positive Rate (TPR) and False Alarm Rate (FAR) as probability metrics.

The Gaussian Mixture Model is basically a subtraction technique, which mainly used for object detection using pixel distribution. For example:

V1,V2,V3,……Vt=I(xi,yi);1≤i≤t

Where Vt denotes the pixel value at time t in video frame, (xi,yi) denotes the coordinate of the pixel in the frame.

During tracking, the changes in appearance of objects by changing the rotation, scale, pose and lighting variations are often. Therefore, the correlation filters are required to adapt to these dynamic changes for tracking the object efficiently. This model is claimed to achieve the accuracy of 88%.

 

### Use:

This paper provides another alternative method to tracking the movement of human which can be applied to the babies. The correlation filters need to modify to the size of babies. This will help us to decide which method is efficient and accurate to track the movement of a baby.
