# Image_Classification

I developed a Convolutional Neural Network (CNN) model to tackle the binary classification problem of classifying images of cats and dogs. Initially, the model consisted of Conv2D and MaxPooling layers. However, it became evident that the model was overfitting the training data, indicated by the training accuracy being much higher than the validation accuracy, which stood at 71%. This discrepancy highlighted the presence of high variance in the model's performance. To address this issue, I implemented Data augmentation and Dropout regularization techniques. Data augmentation involved applying various transformations to increase the diversity of the training data, while Dropout regularization randomly deactivated neurons during training to promote more robust and generalized learning. As a result, the model's performance significantly improved, with the validation accuracy soaring to 82.8%. These enhancements effectively reduced overfitting, allowing the model to achieve better generalization and classification accuracy on unseen images of cats and dogs.

dataset : https://drive.google.com/drive/folders/1QDUvvaa1TSmn0PupspueNVQ-ZNSvIUt-?usp=sharing
