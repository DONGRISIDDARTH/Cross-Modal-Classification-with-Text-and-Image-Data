# Cross-Modal-Classification-with-Text-and-Image-Data
Developed and integrated separate text and image classification models on the 101-food dataset, containing 101 classes. Combined the two models into one hybrid model for improved classification accuracy.


Approach:
Text Classification:

First, I trained the text classification model using BERT (Bidirectional Encoder Representations from Transformers) and HAN (Hierarchical Attention Networks).
The training process was run and logs were saved to monitor performance and fine-tune the model.
Image Classification:

Next, I trained the image classification model using InceptionResNetV2, which is a deep convolutional neural network known for its high accuracy in image recognition tasks.
Similarly, training logs were saved during this process for later analysis.
Fusion (Cross-Modal Classification):

After training the text and image models separately, I concatenated the outputs of both models (text and image).
During the concatenation step, I loaded the saved logs from the text and image models and used them to train the cross-modal classifier.
The final hybrid model utilized features from both text and images to make predictions, leading to an improved classification performance.
Results:
The final cross-modal model achieved an 85% accuracy on the classification task, demonstrating the effectiveness of combining both text and image features for improved classification.
