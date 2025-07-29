# Differentially-Private Stochastic Gradient Descent
* Adds differential privacy to *gradient step*
* Tradeoff between utility and privacy
* **Post-hoc**: gradient access is differentially private (DP) $\rightarrow$ entire model is DP
* Having privacy budget $\epsilon$ ensure weights are private
* **links**:- [Deep Learning with DP](https://arxiv.org/pdf/1607.00133) and [PyTorch DP-SGD](https://medium.com/pytorch/differential-privacy-series-part-1-dp-sgd-algorithm-explained-12512c3959a3)

---
**Results**   
On the MNIST dataset
|Model|Test Accuracy|
| :- | :- |
|Vanilla|97.00%|
|Differentially Private|91.00%|
