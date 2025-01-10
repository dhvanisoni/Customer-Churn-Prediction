# Customer Churn Prediction with ANN
The Multinational Bank Customer Churn dataset is chosen for developing a deep learning model with three different optimizers to predict customer churn. Customer churn, the discontinuation of a customer's relationship with the bank, is a crucial concern for sustainability and growth. By analyzing customer attributes, this dataset aims to develop a model to identify potential churners. The dataset includes features such as credit score, tenure, balance, and customer characteristics.The project aims is to reserach the effectivness of optimizers, implement different optimizers, tune hyperparmeters and compare the results.

[Download The Dataset](https://github.com/dhvanisoni/Customer-Churn-Prediction-with-three-different-State-of-the-art-optimizers/blob/main/Customer_churn.csv)


### Model Selection: ANN
- Objective: Implement an Artificial Neural Network (ANN) for customer churn prediction.
- Action: Created a model using TensorFlow's Keras API, with a Sequential model architecture.
- Result: The model architecture includes dense layers with ReLU activation, batch normalization, and dropout for preventing overfitting. The final output layer uses a sigmoid activation function for binary classification.

### Model Optimization
Three different optimizers were used to evaluate performance:
- **Adam Optimizer**: Achieved a test accuracy of 0.8580 and a test loss of 0.3503. Despite longer training time, Adam showed the most favorable results in accuracy and loss.
- **RMSprop Optimizer**: Demonstrated slightly lower performance with a test accuracy of 0.8570 and a test loss of 0.3557. The accuracy curve showed gradual improvement with some fluctuations.
- **Adagrad Optimizer**: Yielded comparatively lower results with a test accuracy of 0.8390 and a test loss of 0.3882. The accuracy curve exhibited slower and less consistent growth compared to Adam and RMSprop.

### Conclusion
- 🔍 Findings: Adam optimizer outperformed RMSprop and Adagrad in terms of accuracy and loss, despite longer training time. RMSprop showed gradual improvement with some fluctuations, while Adagrad exhibited slower and less consistent growth.
- Implications: The choice of optimizer significantly impacts model performance and efficiency. Adam's adaptive learning rates and momentum contribute to its superior performance, while Adagrad's reliance on historical gradients may limit its effectiveness.
  
This project demonstrates the importance of selecting the right optimizer for deep learning models, with Adam showing the most promising results for customer churn prediction. 
