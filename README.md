## App Features

- Upload multiple images of skin lesions for classification.
- Classify lesions with a pre-trained MobileNetV2 model fine-tuned on a proprietary skin lesion dataset.
- View classification results directly in the app with confidence scores.

## Model Information

- **Architecture**: MobileNetV2 pre-trained on ImageNet.
- **Fine-tuning**: Started from layer 154 of MobileNetV2.
- **Test Accuracy**: 91.04%.
- **Dataset**: Proprietary dataset containing images of benign and malignant skin lesions.

## Training the Model

The model was trained in a Jupyter notebook (`Skin_Cancer.ipynb`) with the following key steps:
- Data preprocessing and augmentation using `ImageDataGenerator`.
- Model definition with TensorFlow's Keras API.
- Fine-tuning on a skin lesion dataset from layer 154.
