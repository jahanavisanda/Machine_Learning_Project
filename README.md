**Swish-LSTM – Improving the forecasting on the COVID-19 transmission rate with a custom loss function**

1. **Objective**: The project aims to forecast the COVID-19 outbreak using machine learning techniques, specifically focusing on the medical domain.

2. **Dataset Preparation**: Data considered was a  time series dataset related to COVID-19 transmission rates. We perform data preprocessing and data normalization , which involves cleaning and organizing the data to make it suitable for training the machine learning models.

3. **Model Architecture**: LSTM is a type of recurrent neural network (RNN) that is commonly used for time series analysis and prediction.LSTM models are designed to address the issue of vanishing gradients in traditional RNNs, which can make it difficult to learn long-term dependencies in time series data. LSTM models use a memory cell and several gates to selectively remember or forget information from previous time steps, allowing them to capture long-term dependencies more effectively.

4. **Swish Activation Function**: We implemented the Swish activation function, which is an alternative to the commonly used ReLU (Rectified Linear Unit) activation function.

5. **Penalty Weight for Underreporting Countries**: To address the issue of underreporting in certain countries, the team introduces a penalty weight. This penalty weight is applied to the underreporting countries, aiming to improve the model's generalization performance which  lead to a significant improvement in the forecast accuracy.

6. **Evaluation Approach**: Adopted a  multi-module evaluation approach to assess the success of the project.We compared the results with the Traditional approach,ReLU,Swish

7. **Success Evaluation**: The success of the project is evaluated based on its impact in the medical domain and its ability to accurately capture the trend of the COVID-19 outbreak. 

8.**Overall Contribution**: The project combines machine learning techniques, time series analysis, and the implementation of the Swish activation function to improve the accuracy of COVID-19 transmission rate forecasting. The findings and technical approach contribute to the field of healthcare and support efforts in combating the pandemic.
