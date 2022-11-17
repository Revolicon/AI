# AI
Icon detection and replacement AI
Slave of this directory is Oğuz Kaan Özsoy


<pre>
#Models

13 Class Multi Classification Model

Model: "sequential10"
__
 Layer (type)                Output Shape              Param #
=================================================================
 conv2d_17 (Conv2D)          (None, 126, 126, 16)      448

 max_pooling2d_17 (MaxPoolin  (None, 63, 63, 16)       0
 g2D)

 conv2d_18 (Conv2D)          (None, 61, 61, 32)        4640

 max_pooling2d_18 (MaxPoolin  (None, 30, 30, 32)       0
 g2D)

 conv2d_19 (Conv2D)          (None, 28, 28, 64)        18496

 max_pooling2d_19 (MaxPoolin  (None, 14, 14, 64)       0
 g2D)

 flatten_10 (Flatten)        (None, 12544)             0

 dense_30 (Dense)            (None, 64)                802880

 dense_31 (Dense)            (None, 128)               8320

 dense_32 (Dense)            (None, 13)                1677

=================================================================
Total params: 836,461
Trainable params: 836,461
Non-trainable params: 0



val_loss: 0.5708 - val_acc: 0.8932
</pre>
![Alt text](acc_metrics.png?raw=true "acc_metrics")

![Alt text](loss_metrics.png?raw=true "loss_metrics")