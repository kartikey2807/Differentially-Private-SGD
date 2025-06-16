# Differentially-Private Stochastic Gradient Descent
* Adds differential privacy to the gradient step
* Tradeoff between utility and privacy
* Evaluated on the MNIST dataset
* **Post-hoc**: gradient access is differentially private (DP) $\rightarrow$ entire model is DP
* Having privacy budget $\epsilon$ ensure weights are private
* [Deep Learning with Differential Privacy](https://arxiv.org/pdf/1607.00133) and [PyTorch Implementation](https://medium.com/pytorch/differential-privacy-series-part-1-dp-sgd-algorithm-explained-12512c3959a3)

---
**Results**   
On the MNIST dataset
|Model|Test Accuracy|
| :- | :- |
|Vanilla|97.00%|
|Differentially Private|91.00%|
