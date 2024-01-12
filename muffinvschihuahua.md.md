Joanne (Seohyeon) Lee
jlee8727@usc.edu
Dataset: Muffin vs Chihuahua

Model development and training: For this data set, I chose a simple CNN model using PyTorch and I tried following the format of the L5 notebook. In this model, I utilized sequence of convolutional layers with max pooling and fully connected layers to differentiate chihuahuas from muffins which can look visually similar to one another. The model was trained applying forward pass, Cross-Entropy loss for calculating loss and backpropagation.

Model Evaluation and Training: The model received an accuracy of 85%, which I consider is pretty accurate in differentiating the two classes.

Discussion: The data set contains appropriate number of images for both classes for unciased learning, model architecture which was a CNN is suited to capture the patterns of the images suitable for the task, and classical training procedures were used which are generally useful for image classification tasks.
There are countless wider uses for this model that could include differentiating edible plants/food from nonedible ones for food safety, for example. If there are limitations, it would be that the model might need a bigger set of data and images for more complex identification/classification.
If I were to continue this project, I would collect more images of muffins and chihuahuas that look very similar to each other to and modify the model for it to be able to handle this similarity and perhaps use different set of data such as the edible and inedible foods mentioned above.