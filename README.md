## HW_practice_nns.
##practice of cnn and rnn evaluation metrics _open_code_other_attribution_ (not mine).

##evaluation of different metrics include: batch_size, epochs, and dropout.

##initial (base) training run results are below.

#x_train shape: (60000, 28, 28, 1)
#60000 train samples
#10000 test samples
#Train on 60000 samples, validate on 10000 samples
#Epoch 1/12
60000/60000 [==============================] - 184s 3ms/step - loss: 0.2588 - acc: 0.9196 - val_loss: 0.0573 - val_acc: 0.9812
#Epoch 2/12
60000/60000 [==============================] - 181s 3ms/step - loss: 0.0907 - acc: 0.9731 - val_loss: 0.0405 - val_acc: 0.9872
#Epoch 3/12
60000/60000 [==============================] - 181s 3ms/step - loss: 0.0672 - acc: 0.9799 - val_loss: 0.0354 - val_acc: 0.9879
#Epoch 4/12
60000/60000 [==============================] - 178s 3ms/step - loss: 0.0562 - acc: 0.9836 - val_loss: 0.0335 - val_acc: 0.9891
#Epoch 5/12
60000/60000 [==============================] - 173s 3ms/step - loss: 0.0480 - acc: 0.9850 - val_loss: 0.0311 - val_acc: 0.9900
#Epoch 6/12
60000/60000 [==============================] - 170s 3ms/step - loss: 0.0433 - acc: 0.9871 - val_loss: 0.0318 - val_acc: 0.9900
#Epoch 7/12
60000/60000 [==============================] - 170s 3ms/step - loss: 0.0394 - acc: 0.9877 - val_loss: 0.0297 - val_acc: 0.9911
#Epoch 8/12
60000/60000 [==============================] - 168s 3ms/step - loss: 0.0364 - acc: 0.9892 - val_loss: 0.0269 - val_acc: 0.9918
#Epoch 9/12
60000/60000 [==============================] - 167s 3ms/step - loss: 0.0324 - acc: 0.9900 - val_loss: 0.0272 - val_acc: 0.9919
#Epoch 10/12
60000/60000 [==============================] - 167s 3ms/step - loss: 0.0301 - acc: 0.9907 - val_loss: 0.0265 - val_acc: 0.9918
#Epoch 11/12
60000/60000 [==============================] - 167s 3ms/step - loss: 0.0275 - acc: 0.9914 - val_loss: 0.0322 - val_acc: 0.9909
#Epoch 12/12
60000/60000 [==============================] - 168s 3ms/step - loss: 0.0277 - acc: 0.9916 - val_loss: 0.0304 - val_acc: 0.9914
#Test loss: 0.030424443268215872
#Test accuracy: 0.9914
