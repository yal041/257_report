# Experiments in original paper
The code of original paper is based on https://github.com/huawei-noah/Disout

## My modification
Since the code has provided full functionality. I did only two modification for my experiments : (1) The model size (2) Replace Disout() with nn.Dropout() to compare Disout against Dropout.

# Extension experiments
The code above does not include Disout for FC, so I refer to another implementation of Disout: https://github.com/tfwcn/tensorflow2-disout

## My modification
Since the code has provided full functionality. I did few modifications for my experiments: (1) Build and change the model size for training MNIST dataset (2) Replace Disout1D() with  tf.keras.layers.Dropout() to compare Disout against Dropout.
