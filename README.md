##HW_practice_nns

##practice of cnn and rnn evaluation metrics _open_source_code_other_attribution_ (not mine)
##dataset MNIST

##version b

##evaluation metric changes as follows:

##batch_size: 128 to 1024

##epochs: 12 to 10

##dropout before flatening: 0.25 to 0.1

##dropout after flatening: 0.5 to 0.25

##net accuracy difference of this run from base = 0.0054 just on changes to the above parameters


#x_train shape: (60000, 28, 28, 1)

#60000 train samples

#10000 test samples

#Train on 60000 samples, validate on 10000 samples

#Epoch 1/10
60000/60000 [==============================] - 218s 4ms/step - loss: 0.6399 - acc: 0.8091 - val_loss: 0.1809 - val_acc: 0.9484

#Epoch 2/10
60000/60000 [==============================] - 216s 4ms/step - loss: 0.1499 - acc: 0.9551 - val_loss: 0.0910 - val_acc: 0.9727

#Epoch 3/10
60000/60000 [==============================] - 217s 4ms/step - loss: 0.0937 - acc: 0.9717 - val_loss: 0.0697 - val_acc: 0.9771

#Epoch 4/10
60000/60000 [==============================] - 218s 4ms/step - loss: 0.0686 - acc: 0.9792 - val_loss: 0.0505 - val_acc: 0.9836

#Epoch 5/10
60000/60000 [==============================] - 220s 4ms/step - loss: 0.0505 - acc: 0.9849 - val_loss: 0.0413 - val_acc: 0.9863

#Epoch 6/10
60000/60000 [==============================] - 221s 4ms/step - loss: 0.0443 - acc: 0.9864 - val_loss: 0.0376 - val_acc: 0.9875

#Epoch 7/10
60000/60000 [==============================] - 217s 4ms/step - loss: 0.0354 - acc: 0.9896 - val_loss: 0.0375 - val_acc: 0.9866

#Epoch 8/10
60000/60000 [==============================] - 215s 4ms/step - loss: 0.0294 - acc: 0.9909 - val_loss: 0.0353 - val_acc: 0.9871

#Epoch 9/10
60000/60000 [==============================] - 215s 4ms/step - loss: 0.0284 - acc: 0.9908 - val_loss: 0.0378 - val_acc: 0.9865

#Epoch 10/10
60000/60000 [==============================] - 217s 4ms/step - loss: 0.0220 - acc: 0.9931 - val_loss: 0.0405 - val_acc: 0.9860

#Test loss: 0.04045569936858956

#Test accuracy: 0.986
