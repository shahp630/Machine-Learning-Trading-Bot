# Machine-Learning-Trading-Bot

![14-challenge-image](https://github.com/shahp630/Machine-Learning-Trading-Bot/assets/133065460/7d9dc3c7-e941-4857-91b8-bf0bfb46578a) 

In this Challenge, you’ll assume the role of a financial advisor at one of the top five financial advisory firms in the world. Your firm constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. In recent years, your firm has heavily profited by using computer algorithms that can buy and sell faster than human traders.

The speed of these transactions gave your firm a competitive advantage early on. But, people still need to specifically program these systems, which limits their ability to adapt to new data. You’re thus planning to improve the existing algorithmic trading systems and maintain the firm’s competitive advantage in the market. To do so, you’ll enhance the existing trading signals with machine learning algorithms that can adapt to new data. 

# Establishing a Baseline Performance

# Generating Trading Signals 
![Screenshot (36)](https://github.com/shahp630/Machine-Learning-Trading-Bot/assets/133065460/a1f23a6f-bd23-43ef-a85e-cc3bc7a9ed4d)

# Plotting Strategy Returns
![Screenshot (37)](https://github.com/shahp630/Machine-Learning-Trading-Bot/assets/133065460/4af1241f-92a9-44d3-93e5-ce8c169fa170)

# Splitting Data into Training and Testing DataSets
![Screenshot (38)](https://github.com/shahp630/Machine-Learning-Trading-Bot/assets/133065460/395a1fc0-39f9-4e85-9499-e4cf144423ed)

# SVC Model Predictions
![Screenshot (39)](https://github.com/shahp630/Machine-Learning-Trading-Bot/assets/133065460/9888877b-0f36-4b14-b6e2-ec8a2dcf82e4)

The classification report shows that at a "signal of 1", the SVC model predictions are only at 56% accuracy. Even with a recall of 100, the model cannot be trusted to accurately predict.

# Predicted, Actual Returns, and Strategy Returns
![Screenshot (40)](https://github.com/shahp630/Machine-Learning-Trading-Bot/assets/133065460/0fb5c0aa-c4dc-46f3-80e6-45961e92aaf9)

The predictions DataFrame showed that over time, the difference between the Actual and Strategy Returns decreased, meaning that over time the Model's accuracy improved over time.

# Cumulative Return Plot
![Screenshot (41)](https://github.com/shahp630/Machine-Learning-Trading-Bot/assets/133065460/62c7b9b6-adb2-4854-bece-2af7fc27fbc7)

The cumulative return plot shows the actual returns vs. the strategy returns. Although it was a bit surprising, the actual returns exactly matched the strategy returns. This proved that our testing and training DataSets and Model Predictions were extremely accurate and can be trusted.

# Evaluating a New Machine Learning Classifier

![Screenshot (42)](https://github.com/shahp630/Machine-Learning-Trading-Bot/assets/133065460/c45356f8-3b19-4011-b138-6b4e88f4443e)
![Screenshot (43)](https://github.com/shahp630/Machine-Learning-Trading-Bot/assets/133065460/54b8d4aa-6824-45c6-8a2a-0206b7cc6bd0)
![Screenshot (44)](https://github.com/shahp630/Machine-Learning-Trading-Bot/assets/133065460/ee8291e7-ed82-4395-9e3d-09b9520bc360)
![Screenshot (45)](https://github.com/shahp630/Machine-Learning-Trading-Bot/assets/133065460/a45c6f29-e2e9-4569-b42f-7a5a28d1cc17)



