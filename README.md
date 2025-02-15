# 📊 Portfolio Optimization Using Bidirectional CNN-LSTM with Attention Mechanism

This project focuses on predicting stock prices using a state-of-the-art deep learning model and providing actionable insights to optimize investment portfolios. Designed as part of **IST 691 - Deep Learning** at Syracuse University under the guidance of **Professor Patrick McSweeny**, this project offers advanced predictive analytics for the financial domain.

## 🌟 Key Features

### Advanced Architecture
- **Bidirectional CNN-LSTM**:
  - **2 CNN layers**: Extract short-term patterns from historical stock data.
  - **2 Bidirectional LSTM layers**: Capture long-term temporal dependencies effectively.
  - **2 Attention layers**: Enhance the model’s ability to focus on important time steps for better predictions.
- Fully integrated pipeline for multi-symbol stock data, ensuring scalability and accuracy.

### Performance
- **Mean Squared Error (MSE)**: Achieved an impressive **5.87**, showcasing robust predictive capabilities even in volatile markets.
- Built for **multi-symbol stock data**, delivering reliable and consistent predictions across datasets.

### User-Centric Features
- Personalized **Buy, Sell, or Hold** recommendations based on predicted trends.
- Configurable thresholds for tailored portfolio management.
- Analyzed **2 years of historical stock data** (via the **yfinance API**) with over **60,000 data points**, enabling comprehensive and data-driven decision-making.



## 📈 Results


## 📊 Model Comparison

We tested three advanced models for stock price prediction using 2 years of historical data and evaluated their performance based on **Average Mean Squared Error (MSE):**

| **Model**                              | **Average MSE** |
|----------------------------------------|-----------------|
| **CNN-Bidirectional LSTM with Attention** | **5.87** (Best)      |
| **CNN-LSTM Based Model**               | **9.74**        |
| **Combined SARIMA CNN-LSTM**           | **38.53**       |

### Key Insights:
1. **CNN-Bidirectional LSTM with Attention** achieved the best performance, demonstrating its ability to effectively capture both long-term and short-term dependencies while focusing on critical time steps through the Attention mechanism.
2. The **CNN-LSTM Based Model** delivered moderate performance, reflecting the benefits of convolutional layers for feature extraction but lacking the full power of bidirectional LSTMs.
3. The **Combined SARIMA CNN-LSTM** approach underperformed, suggesting limited effectiveness when combining traditional statistical methods with deep learning models for this dataset.

### Sample Prediction Graphs
![image](https://github.com/user-attachments/assets/403997f2-9369-47a8-b98c-bf912bc665cf)
![image](https://github.com/user-attachments/assets/3e5e7931-f004-47ff-a6e5-c25090fb16aa)




### Recommendations
The model generates **"Buy," "Sell," or "Hold" recommendations** based on user-defined thresholds, enabling effective portfolio management.
![image](https://github.com/user-attachments/assets/83ffe5d5-00fe-4631-b87e-3e4ce30b13ac)


## 🛠️ Tools and Technologies
- **Programming Languages**: Python
- **Libraries**:
  - Machine Learning: TensorFlow, Keras, NumPy, Pandas
  - Data Visualization: Matplotlib
  - Financial Data: yfinance
- **Deep Learning Components**:
  - Bidirectional LSTMs
  - Attention Mechanisms
  - Convolutional Neural Networks (CNNs)

Special thanks to **Professor Patrick McSweeny** for his guidance and mentorship throughout this project.

## 🤝 Contributing
Contributions are welcome! If you’d like to enhance the project or fix any issues, please fork the repository and submit a pull request.

## 📬 Contact
Feel free to reach out for any questions or collaborations:
- **Name**: Biswadip Bhattacharyya
- **LinkedIn**: (https://www.linkedin.com/in/biswadip-bhattacharyya-3896181b3/)

---

Let me know if you’d like further customization!
