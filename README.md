# computer_vision
Some coll computer vision projects

In this segment, you will see the python implementation of style transfer. For the demonstration, let’s take the image of a rabbit as the content image and splash of colours as the style image. You can, of course, use any set of images for your notebook.

Please note that there is a slight change in notation. The candidate image is denoted by ‘generated image’ in the notebook.

In the case of transfer learning, we use a pre-trained model, VGGNet in our case, and remove its last fully connected layer since our task is not to classify the image. Here, we use the pre-trained weights of the model to update the candidate image instead of updating the model weights. Since there are no prebuilt functions to train these type of networks in Keras,  you will see that we will use lots of custom functions.

 
