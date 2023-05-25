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

![](/images/animals.png "Animals")

### 4. Evaluate the model

First we use confusion matrix to evaluate:

![](/images/cm.png "Animals")

And also we can use t-SNE to evaluate:

![](/images/tsne.png "t-SNE")

This is to test the result of the model.
