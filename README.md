# Transfer Learning with MobileNetV2

- Created training dataset and validation dataset from the directory.
- Implemented Data augmentation techniques such as random flipping and random rotation.
- Ran the pre-trained MobileNetV2 model including the top layer on the custom training dataset.
- Ran the pre-trained MobileNetV2 model by replacing the top layer with a GlobalAveragePooling2D layer followed by a dense layer on the custom training dataset.
- Fine-tuned the model by unfreezing the later final layers.
- Achieved a training set accuracy of 93.9% and a validation accuracy of 92.3%.
