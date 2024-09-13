# Cat vs Dog Image Classification using CNN in TensorFlow

## Project Overview
Developed a high-accuracy image classification model to distinguish between cats and dogs using Convolutional Neural Networks (CNNs) and TensorFlow.

## Key Achievements
• Achieved 94% accuracy on a test set of previously unseen images

• Processed and analyzed a dataset of 25,000 cat and dog images

• Implemented data augmentation techniques to enhance model generalization

## Technical Details
• Framework: TensorFlow 2.x

• Architecture: Custom CNN with the following structure:
  - 3 Convolutional layers with BatchNormalization and MaxPooling
  - Flatten layer
  - 2 Dense layers with Dropout
  - Output Dense layer with 1 unit (binary classification)
• Total Parameters: 14,848,193
• Dataset: 25,000 labeled images of cats and dogs (12,500 each)

## Model Architecture Highlights
• Input Shape: 256x256x3 (inferred from first conv layer)

• Convolutional Layers: 32 filters (3x3), 64 filters (3x3), 128 filters (3x3)

• MaxPooling: Applied after each convolutional layer

• Dense Layers: 128 units and 64 units with dropout for regularization

• Output: Single unit with sigmoid activation for binary classification

## Skills Demonstrated
• Deep Learning

• Convolutional Neural Networks (CNNs)

• TensorFlow

• Python

• Data Preprocessing

• Model Architecture Design and Optimization

## Impact
This project showcases proficiency in building and deploying deep learning models for real-world applications. The techniques used are directly applicable to various image classification tasks across industries such as healthcare, autonomous vehicles, and content moderation.

## Future Directions
• Fine-tune hyperparameters to potentially improve model performance

• Experiment with more advanced architectures like ResNet or EfficientNet

• Develop a web or mobile application for real-time pet classification

• Explore model interpretability techniques to understand decision-making process

---
Feel free to connect if you'd like to discuss this project or explore collaboration opportunities in the field of computer vision and deep learning!

#DeepLearning #ComputerVision #TensorFlow #MachineLearning #AI
