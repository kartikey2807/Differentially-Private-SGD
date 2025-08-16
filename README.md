# Differentially-Private SGD
References: [Abadi, Martin et al.](https://arxiv.org/pdf/1607.00133)   
**Summary**   
* Differential privacy added to *gradient step*
* Tradeoff exists between utility and privacy
* Having privacy budget $\epsilon$ ensure weights are private
* Gradient access private --> Model is differentially private (**post-hoc**)

---
**Results**   
On the MNIST dataset
|Model|Test Accuracy|
| :- | :- |
|Vanilla|97.00%|
|Differentially Private|91.00%|
