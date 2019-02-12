In our code, we have use the Inception V3 model developed at Google, and pre-trained on ImageNet, a large dataset of images (1.4M images and 1000 classes). 
This is a powerful model; let's see what the features that it has learned can do for our apple_scab vs. apple_healthy.

To download the weights get it by running this command :
!wget --no-check-certificate \https://storage.googleapis.com/mledu-datasets/inception_v3_weights_tf_dim_ordering_tf_kernels_notop.h5 \
    -O /tmp/inception_v3_weights_tf_dim_ordering_tf_kernels_notop.h5
    
Also the dataset used in the code is available here :
https://drive.google.com/open?id=1V5LWEEHOqwWUs6sgJFE3IZaf4-8orfzX
