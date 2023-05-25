# A bird or not a bird? That is a question.
This blog is about what I learn on 18th May, 2023. The example code about how to recogonize a bird with *fastai*.
Some basic content can be found [Basic content for fastai course](https://www.fast.ai/posts/2020-01-16-fast_template.html).
## Some steps to implement the model
### 1. Get ready
Check internet and upgrades to the latest version of libraries
### 2. Get all the data needed
Download some essential images for `birds` and `non-birds`
The max image number for each category is 200, acceptable here(cost 2mins and 38s) but if we want to identify 10 different animals, maybe we need to reduce the number.
### 3. Train the model
Split the data into training set and testing set. And we use **block** which is important in classification. 

The model in this example is a resnet based model. ResNet, short for Residual Network, is a deep convolutional neural network (CNN) architecture that was introduced by Kaiming He et al. in 2015, as the following essay describes:

[Deep Residual Learning for Image Recognition.](https://ieeexplore-ieee-org.ezproxy.library.uq.edu.au/stamp/stamp.jsp?tp=&arnumber=7780459)

The basic structure of resnet can be shown below:

![Image of fast.ai logo](images/logo.png)
The most significant difference of reenet with other network model is that it has shortcut connections directly between input and output.

And in the model we are given example of resnet18, which means it has 18 layers.
### 4. Use the trained model

Use the example image to test whether our model works.

This is to test the result of the model.
