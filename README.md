# Player Detector

![Player Detector](https://github.com/ryanro97/player-detector/blob/master/player-detector.gif)

Player detection using [PyTorch's Faster R-CNN model with a ResNet-50-FPN Backbone](https://pytorch.org/docs/stable/torchvision/models.html#faster-r-cnn).

Training and validation images extracted using [FFMPEG](https://www.ffmpeg.org/), and labeled using Tzuta Lin's [LabelImg](https://github.com/tzutalin/labelImg) tool.

Both the [Trainer](https://github.com/ryanro97/player-detector/blob/master/PlayerDetectorTrainer.ipynb) and [Predictor](https://github.com/ryanro97/player-detector/blob/master/PlayerDetectorPredictor.ipynb) can be used to train and predict other objects, however the only data augmentation implemented is a horizontal flip, due to other augmentations not making much sense for player detection.

Further details to setup object detection are in the notebooks.
