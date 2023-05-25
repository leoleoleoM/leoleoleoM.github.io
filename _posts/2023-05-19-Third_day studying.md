# It's my turn now to build a model
In this blog, I will describe how I build my own model based on the given example.
## Detailed steps
### 1. Set up enviroment 
Here we check the internet connection and install *fastai* libraries.

Ok, this part nothing special and all the codes are fixed.
### 2. Collect data
We are using **Duck Duck Go** dataset. So make sure we import all the necessary libaries here, including:

**Duck Duck Go**🦆

**fastcore**

**fastbook**

And then we can download each animal image from what we import.And then download **60** images for each category.
### 3. Pre-process and train
First eliminate all the invalid images. And then use **Datablock** method to train the model. Split the dataset with 80% to train and 20% to test.

The following image can show the category after training:



[Deep Residual Learning for Image Recognition.](https://ieeexplore-ieee-org.ezproxy.library.uq.edu.au/stamp/stamp.jsp?tp=&arnumber=7780459)

The basic structure of resnet can be shown below:

![](/images/architure.png "Structure")

The most significant difference of reenet with other network model is that it has shortcut connections directly between input and output.

And in the model we are given example of resnet18, which means it has 18 layers.
### 4. Use the trained model

Use the example image to test whether our model works.

This is to test the result of the model.
