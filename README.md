# Stock-Price-Prediction-using-Deep-Learning-Methods
Here we developed and compared three deep learning architectures (MLP, LSTM, GRU) for Reliance stock price prediction
This study presents a comparative analysis of three prominent deep learning architectures—Multilayer Perceptron (MLP), Long Short-Term Memory (LSTM), and Gated Recurrent Unit (GRU)—for predicting stock prices of Reliance Industries Limited. Stock price forecasting remains a challenging problem due to the inherent volatility, non-linearity, and complexity of financial markets. By evaluating these three distinct neural network architectures, this research aims to identify the most effective approach for capturing temporal dependencies and patterns in Reliance stock price movements.
Introduction
Stock price prediction has become increasingly important for investors, financial analysts, and portfolio managers seeking to make informed decisions in dynamic markets. Reliance Industries, being one of India's largest conglomerates and a key component of major stock indices, presents an interesting case study due to its market influence and trading volume.
Traditional statistical methods like ARIMA and linear regression often struggle to capture the non-linear relationships inherent in stock price data. Deep learning models, with their ability to learn complex patterns from historical data, have emerged as powerful alternatives for financial forecasting tasks.
Methodology
Data Collection and Preprocessing
Historical stock price data for Reliance Industries was collected, including features such as opening price, closing price, high, low, and trading volume. The data was preprocessed through normalization to ensure all features were on a comparable scale, which is crucial for neural network training.
Model Architectures

Multilayer Perceptron (MLP): A feedforward neural network consisting of multiple fully connected layers. While MLPs are simpler and computationally efficient, they treat each time step independently without explicitly modeling temporal dependencies.
Long Short-Term Memory (LSTM): A recurrent neural network architecture specifically designed to handle sequential data. LSTMs incorporate memory cells with forget, input, and output gates, enabling them to capture long-term dependencies and mitigate the vanishing gradient problem.
Gated Recurrent Unit (GRU): A simplified variant of LSTM with fewer parameters, combining the forget and input gates into a single update gate. GRUs offer computational efficiency while maintaining the ability to model temporal relationships.

Results and Discussion
The comparative analysis revealed distinct performance characteristics across the three architectures:
Performance Metrics: Models were evaluated using metrics such as Mean Absolute Error (MAE), Root Mean Square Error (RMSE), and Mean Absolute Percentage Error (MAPE) to assess prediction accuracy.
Temporal Dependency Modeling: LSTM and GRU networks demonstrated superior capability in capturing sequential patterns compared to MLP, as expected given their recurrent nature and memory mechanisms.
Training Efficiency: GRU models typically required less training time than LSTM while maintaining competitive accuracy, making them an attractive option for real-time applications.
Generalization: The models' performance on test data indicated varying degrees of generalization capability, with proper regularization techniques proving essential to prevent overfitting.
