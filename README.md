# convnets
Exploring the computer vision field of data science. Building, training and evaluating / explaining convolutional neural networks.

## Task: separate dogs from cats

I've processed images, trained a CNN using InceptionV3 as transfer learning and achieved **99.55% test accuracy**. This Google model is really really good.

Here're some of the predictions the ConvNet is making:

<img src='https://github.com/kristofrabay/convnets/blob/main/extra_photos/dog_predictions.PNG' width = 800>


## Evaluation

Here's the confusion matrix on the test set:

<img src='https://github.com/kristofrabay/convnets/blob/main/extra_photos/confusion_matrix.PNG' width = 350>

Used grad-CAM to see what the neural net is *looking for* in an image up until the final dense layers where all spatial information gets lost:

<img src='https://github.com/kristofrabay/convnets/blob/main/extra_photos/gradcam_activations.PNG' width = 300>
