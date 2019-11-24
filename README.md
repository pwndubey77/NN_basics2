## strategy to reduce parameters

   it was observed that reduction in kernel size acheives the reduction in parameters,
   reduction in kernel-size from (16x3x3 then 32x3x3) to (10x3x3 then 20x3x3) reduced params from 16.6k to 14.5k


## Epoch-logs

Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 15s 256us/step - loss: 0.5362 - acc: 0.8483 - val_loss: 0.1071 - val_acc: 0.9775
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 11s 188us/step - loss: 0.2595 - acc: 0.9213 - val_loss: 0.0591 - val_acc: 0.9882
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 11s 185us/step - loss: 0.1987 - acc: 0.9404 - val_loss: 0.0447 - val_acc: 0.9907
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 11s 183us/step - loss: 0.1684 - acc: 0.9470 - val_loss: 0.0369 - val_acc: 0.9909
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 11s 187us/step - loss: 0.1550 - acc: 0.9485 - val_loss: 0.0299 - val_acc: 0.9928
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 11s 187us/step - loss: 0.1390 - acc: 0.9512 - val_loss: 0.0256 - val_acc: 0.9932
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 11s 189us/step - loss: 0.1334 - acc: 0.9524 - val_loss: 0.0290 - val_acc: 0.9919
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 11s 188us/step - loss: 0.1221 - acc: 0.9549 - val_loss: 0.0267 - val_acc: 0.9923
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 11s 186us/step - loss: 0.1167 - acc: 0.9532 - val_loss: 0.0233 - val_acc: 0.9940
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 11s 186us/step - loss: 0.1116 - acc: 0.9558 - val_loss: 0.0213 - val_acc: 0.9942
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 11s 184us/step - loss: 0.1109 - acc: 0.9550 - val_loss: 0.0274 - val_acc: 0.9915
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 11s 184us/step - loss: 0.1062 - acc: 0.9567 - val_loss: 0.0207 - val_acc: 0.9940
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 11s 182us/step - loss: 0.1054 - acc: 0.9555 - val_loss: 0.0202 - val_acc: 0.9941
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 11s 181us/step - loss: 0.1018 - acc: 0.9566 - val_loss: 0.0211 - val_acc: 0.9932
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 11s 189us/step - loss: 0.0998 - acc: 0.9561 - val_loss: 0.0181 - val_acc: 0.9946
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 11s 183us/step - loss: 0.0981 - acc: 0.9572 - val_loss: 0.0217 - val_acc: 0.9934
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 11s 183us/step - loss: 0.0957 - acc: 0.9573 - val_loss: 0.0187 - val_acc: 0.9946
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 11s 188us/step - loss: 0.0938 - acc: 0.9585 - val_loss: 0.0188 - val_acc: 0.9945
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 11s 184us/step - loss: 0.0945 - acc: 0.9566 - val_loss: 0.0192 - val_acc: 0.9947
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 11s 181us/step - loss: 0.0918 - acc: 0.9581 - val_loss: 0.0168 - val_acc: 0.9955
<keras.callbacks.History at 0x7fe3cac42588>

## Score
[0.016795967263798228, 0.9955]
