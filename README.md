## CATS vs DOGS Classification using Convolutional Neural Networks and Data Augmentation


### Dataset Details

  you can download dataset from <a href = "https://storage.googleapis.com/mledu-datasets/cats_and_dogs_filtered.zip" target="_blank">google apis</a>.<br>

#### Dataset Description

Dataset contain 3000 images of Cats and Dogs,
we will train our model on 1700 images,710 images for validation and 604 images for testing.<br><br>
Training Images of cats = 850<br>
Training Images of dogs = 850<br>

Validation Images of Cats = 352<br>
Validation Images of Dogs = 358<br>

Testing Images of Cats = 304<br>
Testing Images of Dogs = 300<br>

### Overfiting and Underfitting aviodence Techniques Used

1-Data Augmentation (zoom,horizontal_flip,rotation)<br>
2-Dropout<br>

### Model Summary

I used convolutional neural networks with 32, 64 and 128 layers.<Br>
<img src = "/Other-images/seq.jpg"><br><br>
<b>Training and Validation Graph:</b><br>
<img src = "/Other-images/training.png"><br>

### Results
Achieved 84% Accuracy on Training data with <b><i>epochs = 100</i></b><br>
81% accuracy on validation data<br>
80% accuracy on testing data<br>
