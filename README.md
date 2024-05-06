# CNN_MNIST_CorNoise_predict

Model: "sequential_18"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 normalization_5 (Normalizat  (None, 28, 28, 1)        3         
 ion)                                                            
                                                                 
 conv2d_40 (Conv2D)          (None, 28, 28, 16)        160       
                                                                 
 max_pooling2d_40 (MaxPoolin  (None, 14, 14, 16)       0         
 g2D)                                                            
                                                                 
 conv2d_41 (Conv2D)          (None, 14, 14, 128)       18560     
                                                                 
 max_pooling2d_41 (MaxPoolin  (None, 7, 7, 128)        0         
 g2D)                                                            
                                                                 
 flatten_18 (Flatten)        (None, 6272)              0         
                                                                 
 dense_36 (Dense)            (None, 1024)              6423552   
                                                                 
 dropout_10 (Dropout)        (None, 1024)              0         
                                                                 
 dense_37 (Dense)            (None, 10)                10250     
                                                                 
=================================================================
Total params: 6,452,525
Trainable params: 6,452,522
Non-trainable params: 3
