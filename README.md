# Transfer-Learning-and-Data-Agmentation-on-Natural-Scene-Dataset
Implementing Transfer Learning and Data Augmentation using Base Model, VGG16 and ResNet50for image classification.<br>

Given :<br>
Train Images : 14k images classified into 6 categories <br>
Validation Images : 3k images classified into 6 categories <br>
Test Images : 7k images without any classification <br>

Regularization:<br>
Early Stopping, Batch Normalization and Dropout<br>


Visualization of test data:<br>
![777](https://user-images.githubusercontent.com/74530146/103931111-96d1fb80-5141-11eb-9470-1037809c29d1.png)

Table of Contents:<br>
* [Code](https://github.com/AamnaBhatti/Transfer-Learning-and-Data-Augmentation-on-Natural-Scene-Dataset/tree/main/Code)
* [CheckPoints](https://github.com/AamnaBhatti/Transfer-Learning-and-Data-Augmentation-on-Natural-Scene-Dataset/tree/main/CheckPoints)
* [Results](https://github.com/AamnaBhatti/Transfer-Learning-and-Data-Augmentation-on-Natural-Scene-Dataset/tree/main/Results)


Result:

| Attempt | Base Model | VGG16 | ResNet50 |
| :-: | :-: | :-:| :-: |
| Original Dataset |  83.6% | - | - |
| Transfer Learning  |  - | 84.7% | 51.4% |<br>
| Transfer Learning & Data Augmentation |  - | 83.2 | 44.4 |<br>
