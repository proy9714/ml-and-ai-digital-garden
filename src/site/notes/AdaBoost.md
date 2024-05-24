---
{"dg-publish":true,"permalink":"/ada-boost/","tags":["trees","boosting","ensemble-learning"],"noteIcon":"2","updated":"2024-05-24T14:04:44.754+05:30"}
---


AdaBoost, short for Adaptive Boosting, is a technique that combines multiple weak learners (simple models) to create a strong overall model. Here’s how it works in simple steps:

1. **Start with Equal Weights**: All data points are initially given equal importance (weight).
2. **Train a Weak Learner**: Train a simple model (like a decision stump) on the data.
3. **Calculate Errors**: See which data points are misclassified by the model.
4. **Update Weights**: Increase the weights of the misclassified data points so that the next model focuses more on them.
5. **Repeat**: Train another weak learner on the updated weights and repeat the process.
6. **Combine Models**: The final prediction is a weighted vote of all the weak learners.


<iframe title="AdaBoost, Clearly Explained" src="https://www.youtube.com/embed/LsK-xG1cLYA?start=60&amp;feature=oembed" height="113" width="200" allowfullscreen="" allow="fullscreen" style="aspect-ratio: 1.76991 / 1; width: 100%; height: 100%;"></iframe>
