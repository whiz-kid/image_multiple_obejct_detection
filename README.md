# multiple_obejct_detection
Convultion Neural Network implemented in Keras Framework to detect multiple object in an image and classify it as well.

Model Layers :

Layer (type)                 Output Shape              Param #   
=================================================================
conv2d_9 (Conv2D)            (None, 32, 100, 100)      896       
_________________________________________________________________
activation_13 (Activation)   (None, 32, 100, 100)      0         
_________________________________________________________________
conv2d_10 (Conv2D)           (None, 32, 98, 98)        9248      
_________________________________________________________________
activation_14 (Activation)   (None, 32, 98, 98)        0         
_________________________________________________________________
max_pooling2d_5 (MaxPooling2 (None, 32, 49, 49)        0         
_________________________________________________________________
dropout_7 (Dropout)          (None, 32, 49, 49)        0         
_________________________________________________________________
conv2d_11 (Conv2D)           (None, 64, 49, 49)        18496     
_________________________________________________________________
activation_15 (Activation)   (None, 64, 49, 49)        0         
_________________________________________________________________
conv2d_12 (Conv2D)           (None, 64, 47, 47)        36928     
_________________________________________________________________
activation_16 (Activation)   (None, 64, 47, 47)        0         
_________________________________________________________________
max_pooling2d_6 (MaxPooling2 (None, 64, 23, 23)        0         
_________________________________________________________________
dropout_8 (Dropout)          (None, 64, 23, 23)        0         
_________________________________________________________________
flatten_3 (Flatten)          (None, 33856)             0         
_________________________________________________________________
dense_5 (Dense)              (None, 512)               17334784  
_________________________________________________________________
activation_17 (Activation)   (None, 512)               0         
_________________________________________________________________
dropout_9 (Dropout)          (None, 512)               0         
_________________________________________________________________
dense_6 (Dense)              (None, 5)                 2565      
_________________________________________________________________
activation_18 (Activation)   (None, 5)                 0         
=================================================================
Total params: 17,402,917
Trainable params: 17,402,917
Non-trainable params: 0
