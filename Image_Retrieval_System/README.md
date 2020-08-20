# Image Retrieval System

This projects is to retrieve images similar to a query image implementing a simple Neural Network. **Flowers dataset** was used for experiments. 

I tuned parameters on pre-trained models for the task of minimizing the Triplet Loss. I experimented with the following models (pre-trained on ImageNet):
- VGG16
- MobileNetV2
- ResNet50
- BigTransfer (also referred to as BiT) which is essentially a ResNet50 but pre-trained on a larger dataset


I referred to the code of first three model callback from [here](https://nbviewer.jupyter.org/github/GoogleCloudPlatform/training-data-analyst/blob/master/courses/fast-and-lean-data-science/keras_flowers_gputputpupod_tf2.1.ipynb).

While using the BiT model I used what is referred to as the BiT-HyperRule. BiT models come in [different variants](https://tfhub.dev/google/collections/bit/1), this variant - `m-r50x1` is used in  my model 
Refer to [post](https://blog.tensorflow.org/2020/05/bigtransfer-bit-state-of-art-transfer-learning-computer-vision.html) to know more about BiT and this rule in general.








