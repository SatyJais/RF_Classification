# RegressionAnalysis

## Case Scenario-
You are a data professional in a data analytics firm called Automatidata. Their client, the New York City Taxi & Limousine Commission (New York City TLC), was impressed with the work you have done and has requested that you build a machine learning model to predict if a customer will not leave a tip. They want to use the model in an app that will alert taxi drivers to customers who are unlikely to tip, since drivers depend on tips.

But, creating a model to predict if a customer is likely to tip can create biases and lead to impaired customer service. 
In case of false positives, where the model says that the customer will give a tip, and they don't, the cab driver will be agitated by the loss in revenue(tip) even after providing better service. In case of a false negative, when the model predicts that the customer will not tip, and they eventually tip, the customer will be at a service loss. This brings bias in the service. The cab driver may choose to serve more people who are more likely to tip. 
**This does not follow the ethical guidelines for data professionals.**

**Alternatively, we can modify the objective to make it more inclusive and free of bias. **

### The model can be trained to find only the generous tippers(>20%) and not mark people who are not likely to tip. Also the information given to the cab drivers should focus on areas of improvement that can eventually help them get better tips instead of flagging users as tippers or non-tippers
