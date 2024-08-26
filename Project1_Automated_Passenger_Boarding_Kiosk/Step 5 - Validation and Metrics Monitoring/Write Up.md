# Reflection on Azure Cognitive Resource-Specific Problems

The project faced two significant challenges: timeout issues with the Azure Computer Vision API and object detection challenges with Azure Custom Vision.

**Timeout Issues with Azure Computer Vision API:**

- Occasional timeouts during facial recognition tasks.
- Resolved by optimizing image/video sizes, implementing batch processing, and adding a retry mechanism.

**Object Detection Challenges with Azure Custom Vision:**

- Limited training images affected model performance in object detection of lighters.
- This can be addressed by increasing training data or augmentation of data.

Despite these challenges, our strategies not only overcame them but also significantly enhanced the performance of the AI components in the automated passenger boarding kiosk application.
