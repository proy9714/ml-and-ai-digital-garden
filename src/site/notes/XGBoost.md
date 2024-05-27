---
{"dg-publish":true,"permalink":"/xg-boost/","tags":["ensemble-learning","boosting"],"noteIcon":"2","updated":"2024-05-27T20:23:47.636+05:30"}
---



**Gradient Boosting** is a general technique for creating a strong predictive model by combining multiple weaker models, typically decision trees. It builds the model in a stage-wise fashion, where each new tree corrects errors made by the previous trees. The general idea is to optimize a loss function iteratively.

**XGBoost**, which stands for Extreme Gradient Boosting, is an optimized implementation of the gradient boosting framework. The "Extreme" part comes from several improvements and optimizations that make it faster and more efficient compared to traditional Gradient Boosting methods. These enhancements include:

1. **Regularization**: XGBoost includes L1 and L2 regularization to prevent overfitting.
2. **Parallelization**: XGBoost can build trees in parallel, significantly speeding up the training process.
3. **Tree Pruning**: It uses a more efficient way of pruning trees, which helps in controlling the complexity of the model.
4. **Handling Missing Values**: XGBoost can automatically handle missing data by learning which missing values are optimal for splits.
5. **Sparsity Awareness**: It efficiently handles sparse data (data with a lot of missing values).
6. **Custom Objective and Evaluation Functions**: XGBoost allows for customized objective functions and evaluation metrics, providing flexibility to tailor the model to specific needs.

These improvements make XGBoost particularly powerful and popular in many machine learning competitions and real-world applications with lots of data.

## Resources

### Fantastic Conceptual Playlist

> [!info]
> - Perhaps the only videos required to form an intuition are videos 1 (Introduction) and 4 (Special features).
> - **The concept is highly complex (especially episode 4), so other than being familiar with the terms I would not recommend getting hung up on the nitty-gritty details!**


<iframe src="https://www.youtube.com/embed/videoseries?list=PLblh5JKOoLULU0irPgs1SnKO6wqVjKUsQ" height="113" width="200" allowfullscreen="" allow="fullscreen" style="aspect-ratio: 1.76991 / 1; width: 100%; height: 100%;"></iframe>
