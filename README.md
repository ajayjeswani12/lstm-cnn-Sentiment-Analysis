# lstm-cnn-Sentiment-Analysis
Research Questions
This project aims to address the following research questions:
1. How effective are different machine learning models, specifically Long Short-Term Memory (LSTM) networks and Convolutional Neural Networks (CNN), in performing sentiment analysis on Amazon reviews?
2. What are the strengths and weaknesses of LSTM and CNN models in terms of accuracy, training time, and computational resources?
3. Can the combination of LSTM and CNN models improve the performance of sentiment analysis?
Results
LSTM Model: The LSTM model achieved an accuracy of 84.06% on sentiment analysis, demonstrating its capability to capture long-range dependencies and contextual information in sequential data. The fluctuations in validation accuracy and loss during training suggest some instability, possibly due to model complexity or data characteristics.
CNN Model: The CNN model achieved a higher accuracy of 86.59% on image classification, showcasing its effectiveness in extracting spatial features and patterns from image data. The rapid convergence and high training accuracy indicate efficient learning of relevant features.
The combination of LSTM and CNN: models can potentially improve sentiment analysis performance due to their complementary strengths in capturing local features and long-term dependencies. However, the current implementation shows signs of overfitting, with high training accuracy but declining validation accuracy. To truly enhance performance, careful tuning and regularization are necessary to improve the model's generalization capabilities.
