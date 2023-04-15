# Alzheimer-recognition-with-Neural-Network
link to pre-trained model https://drive.google.com/file/d/1qDRLOSia6eNHJrwL-7g-nDOGgXYRccy_/view?usp=sharing
# model summary
Model: "sequential_22"
_________________________________________________________________
 Layer (type)                Output Shape              Param    
=================================================================
 conv2d_38 (Conv2D)          (None, 206, 174, 32)      320       
                                                                 
 max_pooling2d_38 (MaxPoolin  (None, 103, 87, 32)      0         
 g2D)                                                            
                                                                 
 conv2d_39 (Conv2D)          (None, 101, 85, 64)       18496     
                                                                 
 max_pooling2d_39 (MaxPoolin  (None, 50, 42, 64)       0         
 g2D)                                                            
                                                                 
 conv2d_40 (Conv2D)          (None, 48, 40, 128)       73856     
                                                                 
 max_pooling2d_40 (MaxPoolin  (None, 24, 20, 128)      0         
 g2D)                                                            
                                                                 
 flatten_22 (Flatten)        (None, 61440)             0         
                                                                 
 dense_63 (Dense)            (None, 64)                3932224   
                                                                 
 dense_64 (Dense)            (None, 4)                 260       
                                                                 
=================================================================

Total params: 4,025,156

Trainable params: 4,025,156

Non-trainable params: 0
_________________________________________________________________


Dataset used:
Alzheimer's Dataset on kaggle (https://www.kaggle.com/datasets/tourist55/alzheimers-dataset-4-class-of-images)
