# Fix_Resnet50_gender_classification
* paper reference: Face and Gender Recognition System Based onConvolutional Neural networks

[image-20201111144240133](C:\Users\Yuhwan\AppData\Roaming\Typora\typora-user-images\image-20201111144240133.png](https://github.com/Kimyuhwanpeter/TF-2.3.0_Fix_resnet50_for_gender/blob/main/1.JPG)

# Implementation
* Ubuntu 18.04
* Python 3.7.8
* tensorflow 2.3.0

# Detail
* This version is modified resnet-50 training in this paper.
* 2-fold cross validiation (different from paper)
* Use test accuracy during training instead of validation accuracy
