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
### 4. Use the trained model
Use the example image to test whether our model works.
