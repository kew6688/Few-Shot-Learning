# Kaggle Competetion
- Using Colab
- Colab Pro (High-RAM mode) is required. Otherwise, the resnet50 will crush program due to RAM overflow

I used ResNet50 model, trained with 50 epochs.
Different training data set by augmentation and transformation:
The first data set is augmented, that all images are center cropped.
The second one is the color transformed by using ColorJitter. Training with different brightness seems very helpful.
The third one is the original set.
Different training optimizors are compared: Adam is more realistic than SGD, since it converges faster.
