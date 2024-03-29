# Unsupervised Learning
## Introduction
Unsupervised learning is one of three important categories of machine learning. Unsupervised learning is often used for data mining, and the data sets it uses are unlabeled. Unsupervised learning classifies data sets by learning the unlabeled data sets and revealing the laws and characteristics that exist in the data. Clustering is one of the main methods in unsupervised learning. It includes algorithms such as K-means and OPTICS, which can effectively distinguish data. Unsupervised learning has a wide range of applications in areas such as image processing and artificial intelligence.

## Summary of references
Unsupervised Learning of Object Keypoints for Perception and Control   
- In this paper, the author learns the original video through the unsupervised learning method, and uses the key bottleneck to transfer the image features between video frames, which can track the object more accurately in a longer time range. People can flexibly represent key points of the object for effective control and reinforcement learning.     

Unsupervised Natural Image Patch Learning
- In this paper, for unlabeled images, the authors used an unsupervised method of embedding natural image patches. The similarity of the two patches can be understood from the prevalence of spatial similarity in natural images.   

Unsupervised learning of Consensus Maximization for 3D Vision Problems
- It is difficult to use supervised learning in 3D vision. In order to solve some problems in 3D vision, this paper uses unsupervised learning that can adapt to any data distribution to achieve consensus maximization. With this method, we solved the problems in 3D vision such as 3D-3D matching, image-to-image matching, and the like. The result of this method is better than RANSAC.   

Guiding new physics searches with unsupervised learning
- In order to obtain new phenomena in the data, this paper proposes a scientific application based on unsupervised learning to detect the difference between two data sets. This method can be applied to synthesis of Gaussian data and the like.

## Pros & Cons
### Pros
- The data sets processed by unsupervised learning do not require tags, and the range of unsupervised learning applications is extensive.
- Unsupervised learning can analyze and extract similar features of a data set.
- Unsupervised learning has a variety of methods such as K-means, self-encoders, and principal component analysis.

### Cons
- Unsupervised learning has limitations and sometimes does not yield satisfactory results.
- The results of unsupervised learning are often inferior to supervised learning.

## Recommendations
Unsupervised learning is useful when dealing with unlabeled data sets. If you want to understand unsupervised learning, I think we must first understand the meaning and application scenarios of unsupervised learning, and then understand some of the algorithms that are often used. We need to understand the principles of these algorithms, the effects, and their advantages and disadvantages, and then implement these algorithms in code. When applied to a dataset, we first need to analyze the dataset and then process the dataset using the appropriate algorithm.

## Conclusions
Unsupervised learning is primarily used to process unlabeled data sets. It contains a variety of processing methods, such as K-means algorithm, hierarchical clustering algorithm, t-SNE clustering, principal component analysis and so on. When using unsupervised learning, select the appropriate algorithm based on the characteristics of the data set to obtain a more excellent clustering effect.

## References
[1] Unsupervised Learning of Object Keypoints for Perception and Control.Tejas Kulkarni, Ankush Gupta, Catalin Ionescu, Sebastian Borgeaud, Malcolm Reynolds, Andrew Zisserman, Volodymyr Mnih.   

[2] Unsupervised natural image patch learning.Dov Danon, Hadar Averbuch-Elor, Ohad Fried, and Daniel Cohen-Or.Computational Visual Media.Vol.5, No.3, September 2019, 229–237.

[3] Unsupervised learning of Consensus Maximization for 3D Vision Problems.Thomas Probst, Danda Pani Paudel, Ajad Chhatkuli, Luc Van Gool.Computer Vision Laboratory, ETH Zurich, Switzerland.   

[4] Guiding new physics searches with unsupervised learning.Andrea De Simone, Thomas Jacques.The European Physical Journal C.April 2019, 79:289.

## Summary of other reports
### Yuan Wei's Report
- This report introduces the structure and main methods of object segmentation based on machine learning.    
- In object segmentation, neural networks play an important role. In the upsampling method, the pooling and unpooling operations can change the sampling of the resolution. Transposed convolution has a better effect and can be used to build upsampled learning. A full convolutional network is another convenient method. The network can meet the needs of any size input and produce an output of corresponding size. The convenience of the U-Net architecture is that the stacked convolutional layers can be replaced with advanced "blocks".   

### Lin Yufeng's Report
- This report uses Tensorflow for image classification and gives the results.
- Tensorflow has a good effect on image processing and can be used to identify images and classify images. In Lin's attempt, 60,000 images were used to train the model, which achieved good results. So when using machine learning, a large training data set is very important.

### Xia Yaqun's Report
- This report summarizes two articles and details the advantages and disadvantages of unsupervised learning and learning methods.
- Unsupervised learning is less complex than supervised learning and has low requirements for data sets. In unsupervised learning, there is no need to mark data sets. However, unsupervised learning cannot determine the results of the analysis. In practical applications, supervised learning often yields better results.

### Jiang Lingtao's Report
- This report introduces the principle of image recognition using a computer and the image recognition algorithm YOLO.
- In a computer, an image is actually a two-dimensional matrix. Image pairs can be classified by taking key features of the matrix. The prediction module required in image recognition can be done with neural networks. YOLO uses only convolutional layers for efficient object detection.


