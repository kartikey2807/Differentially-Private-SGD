## Differentially-Private Stochastic Gradient Descent
Adds differential privacy to the gradient descent step in ML model training. By the property of **post-hoc**, if gradient access is differentially private, so is the entire model. There is a **tradeoff** between utility and privacy. Performance is compared on the MNIST dataset. Having a privacy budget ($\epsilon$) ensure that your weights are private and that original information cannot be extracted. References :- [Deep Learning with Differential Privacy](https://arxiv.org/pdf/1607.00133) and [PyTorch Implementation](https://medium.com/pytorch/differential-privacy-series-part-1-dp-sgd-algorithm-explained-12512c3959a3)

---
**Result**   
On the MNIST dataset
|Model|Test Accuracy|
| :- | :- |
|Vanilla|~97%|
|Differentially Private|~91%|
