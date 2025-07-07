#  Major Assignment 2 - Dog Breed Identification

##  Model Architecture
- Base: `EfficientNetB0` (pre-trained on ImageNet)
- Layers: GlobalAveragePooling2D + Dense(120) with Softmax
- Loss: Categorical Crossentropy
- Optimizer: Adam
- Epochs: 3

##  Transfer Learning Strategy
- EfficientNetB0 base frozen
- Custom head trained on 2000 images
- Trained for 3 epochs using GPU on Google Colab

##  Performance
- Train Accuracy: 83%
- Validation Accuracy: ~0.5% (due to small data subset)
- Submission Format: Multi-class probabilities over 120 breeds

## How to Load Model

```python
from tensorflow.keras.models import load_model
model = load_model("cnn_model.h5")
