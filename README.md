## Towards a regularity theory for ReLU networks (construction of networks, ReLU derivative at zero, theory) 

`regularity_of_relu_networks.ipynb`: 
* PyTorch implementation of deep networks approximating Sobolev-regular functions w.r.t. weaker Sobolev norms. 
* analysis of the backpropagated derivative for which the derivative of the ReLU is set to zero at the origin: Although we can show that the backpropagated derivative coincides almost everywhere with the true derivative, on a nullset the backpropagated derivative can be arbitrary wrong

`custom_ReLU.ipynb`/`fastai_custom_ReLU.ipynb`:
* Testing how often the ReLU derivative gets evaluated at the origin (where it is artifically set to 0) and whether this affects the training (AlexNet, ResNet implementation in PyTorch/using fast.AI hooks) 

For more information, see: [Towards a regularity theory for ReLU networks -- chain rule and global error estimates
](https://arxiv.org/abs/1905.04992)
