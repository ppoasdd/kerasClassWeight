# kerasClassWeight

The keras 1.2.2 does not support class_weight argument with 4 dimensional labels in model.fit.

I changed a few lines to use class_weight with my fully convolution model.

substitutes these keras engine file into /path-to-keras/engine/training.py


