# Cats vs Dogs classification using convolutional neural networks (CNN) and data augmentation 🚀

**Dataset Details**

👉 you can download dataset from <a href = "https://storage.googleapis.com/mledu-datasets/cats_and_dogs_filtered.zip" target="_blank">google apis</a>.<br>

**Dataset Description**

The dataset contains 3000 images of Cats and Dogs. We will train our model on 1700 images,710 images for validation, and 604 images for testing.

<table border="1" cellpadding="8" cellspacing="0" style="border-collapse: collapse; text-align: center;">
  <thead style="background-color: #f2f2f2;">
    <tr>
      <th>Dataset Split</th>
      <th>Cats</th>
      <th>Dogs</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Training Images</td>
      <td>850</td>
      <td>850</td>
    </tr>
    <tr>
      <td>Validation Images</td>
      <td>352</td>
      <td>358</td>
    </tr>
    <tr>
      <td>Testing Images</td>
      <td>304</td>
      <td>300</td>
    </tr>
  </tbody>
</table>

**Overfitting and Underfitting Avoidance Techniques Used**

- Data Augmentation (zoom,horizontal_flip, rotation)
- Dropout

**Model Summary**

I used convolutional neural networks with 32, 64, and 128 layers.

<img src = "/Other-images/seq.jpg">

**Training and Validation Graph**

<img src = "/Other-images/training.png">

**Results**

- ✅ Achieved 84% Accuracy on Training data with <i>epochs = 100</i>
- ✅ 81% accuracy on validation data
- ✅ 80% accuracy on testing data
