# Differentially-Private Stochastic Gradient Descent
References: [Abadi, Martin et al.](https://arxiv.org/pdf/1607.00133)
* Differential privacy to *gradient step*
* Tradeoff exists between utility and privacy
* **Post-hoc**: gradient access is differentially private (DP) $\rightarrow$ entire model is DP
* Having privacy budget $\epsilon$ ensure weights are private

---
**Results**   
On the MNIST dataset
|Model|Test Accuracy|
| :- | :- |
|Vanilla|97.00%|
|Differentially Private|91.00%|
