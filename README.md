## strategy to reduce parameters

   it was observed that reduction in kernel size acheives the reduction in parameters,
   reduction in kernel-size from (16x3x3 then 32x3x3) to (10x3x3 then 20x3x3) reduced params from 16.6k to 13.5k


## Epoch-logs

Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 17s 281us/step - loss: 0.5279 - acc: 0.8519 - val_loss: 0.0933 - val_acc: 0.9810
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 11s 189us/step - loss: 0.2552 - acc: 0.9242 - val_loss: 0.0608 - val_acc: 0.9866
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 11s 189us/step - loss: 0.1960 - acc: 0.9405 - val_loss: 0.0528 - val_acc: 0.9877
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 11s 190us/step - loss: 0.1735 - acc: 0.9440 - val_loss: 0.0438 - val_acc: 0.9873
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 12s 193us/step - loss: 0.1497 - acc: 0.9507 - val_loss: 0.0314 - val_acc: 0.9922
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 11s 189us/step - loss: 0.1370 - acc: 0.9528 - val_loss: 0.0294 - val_acc: 0.9916
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 11s 190us/step - loss: 0.1311 - acc: 0.9531 - val_loss: 0.0259 - val_acc: 0.9930
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 11s 188us/step - loss: 0.1252 - acc: 0.9523 - val_loss: 0.0238 - val_acc: 0.9944
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 11s 178us/step - loss: 0.1160 - acc: 0.9552 - val_loss: 0.0219 - val_acc: 0.9936
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 11s 176us/step - loss: 0.1139 - acc: 0.9550 - val_loss: 0.0238 - val_acc: 0.9929
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 11s 176us/step - loss: 0.1112 - acc: 0.9551 - val_loss: 0.0212 - val_acc: 0.9933
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 11s 176us/step - loss: 0.1066 - acc: 0.9552 - val_loss: 0.0240 - val_acc: 0.9933
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 11s 175us/step - loss: 0.1023 - acc: 0.9571 - val_loss: 0.0211 - val_acc: 0.9938
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 10s 174us/step - loss: 0.0997 - acc: 0.9579 - val_loss: 0.0199 - val_acc: 0.9938
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 10s 174us/step - loss: 0.1006 - acc: 0.9566 - val_loss: 0.0210 - val_acc: 0.9941
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 11s 175us/step - loss: 0.0975 - acc: 0.9565 - val_loss: 0.0199 - val_acc: 0.9945
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 10s 175us/step - loss: 0.0986 - acc: 0.9569 - val_loss: 0.0216 - val_acc: 0.9939
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 11s 178us/step - loss: 0.0945 - acc: 0.9571 - val_loss: 0.0200 - val_acc: 0.9943
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 11s 176us/step - loss: 0.0958 - acc: 0.9571 - val_loss: 0.0202 - val_acc: 0.9947
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 10s 173us/step - loss: 0.0921 - acc: 0.9580 - val_loss: 0.0192 - val_acc: 0.9945
<keras.callbacks.History at 0x7fb844d86a58>

## Score
[0.01919710940934019, 0.9945]
