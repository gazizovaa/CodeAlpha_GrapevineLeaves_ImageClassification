# CodeAlpha_GrapevineLeaves_ImageClassification

#### Dataset: https://www.kaggle.com/datasets/muratkokludataset/grapevine-leaves-image-dataset

Using TensorFlow, I combined data augmentation, CNN architectures, and transfer learning to create a model that performs and adapts:

- started by preprocessing with ImageDataGenerator, applying normalization and validation splits;

- built multiple CNN models, experimenting with BatchNormalization, Dropout, and tuning learning rates;

- added augmented data and tracked progress with loss/accuracy curves to improve generalization;

- incorporated early stopping and checkpointing to avoid overfitting.

The game-changer was transfer learning with pre-trained models like ResNet and EfficientNetV2, boosting feature extraction. 
