---
{"dg-publish":true,"permalink":"/cross-validation/","noteIcon":"","updated":"2024-05-22T15:02:07.553+05:30"}
---


## What is [[Cross Validation\|Cross Validation]]?

Cross-validation is a technique used in machine learning to evaluate the performance of a model and estimate its generalization ability. It helps assess how well the model will perform on unseen data.

In cross-validation, the available data is divided into two parts: the training set and the validation set. The model is trained on the training set and then evaluated on the validation set. This process is repeated multiple times, with different subsets of data used for training and validation each time.

The most common form of cross-validation is called k-fold cross-validation. In k-fold cross-validation, the data is divided into k equally sized subsets or "folds." The model is trained on k-1 folds and validated on the remaining fold. This process is repeated k times, each time using a different fold as the validation set. The performance results from each fold are averaged to obtain an overall performance estimate of the model.

Cross-validation helps address the issue of overfitting, which is when a model performs well on the training data but poorly on new, unseen data. By evaluating the model on multiple subsets of data, cross-validation provides a more robust estimate of how well the model will generalize to unseen data.

It's important to note that cross-validation is typically used during the model development and tuning phase, not during the final evaluation on a completely independent test set. The final evaluation is usually performed on a separate test set that the model has never seen before.

In summary, cross-validation is a technique in machine learning that involves dividing the data into training and validation sets, repeatedly training and evaluating the model on different subsets of data. It helps assess the model's performance and generalization ability, providing a more reliable estimate of how well the model will perform on unseen data.

---

## Resources

### A Simple Explanation to Grasp the Requirement and Concept of K-fold Cross Validation

<iframe src="https://www.youtube.com/embed/fSytzGwwBVw?list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF" height="113" width="200" allowfullscreen="" allow="fullscreen" style="aspect-ratio: 1.76991 / 1; width: 100%; height: 100%;"></iframe>

---

### For Those Who Need a Little More Depth and Explanation about Cross Validation

**Questions Answered**:
- Holdout vs Cross Validation
- When to use which?

<iframe title="Cross Validation Explained!" src="https://www.youtube.com/embed/a86WxNgMv7E?start=10&amp;feature=oembed" height="113" width="200" allowfullscreen="" allow="fullscreen" style="aspect-ratio: 1.76991 / 1; width: 100%; height: 100%;"></iframe>

---
