
## Sigmoid

$$\frac{1}{1+e^{-x}}$$

- Slope is nearly zero for exreme value ➡️ Vanishing gradient problem
- Not zero-centered

## tanh

$$tanh(x)$$

- Zero-centered
- Still vanishing gradient problem

## ReLU

$$max(0, x)$$

> Most widely/generally used

- Faster (~6x) than sigmoid/tanh
- Biologically similar
- 0 slope for negative value ➡️ dead ReLU problem
- Not zero-centered

## Leaky ReLU

$$max(0.01x, x)$$

- No dead ReLU problem

## Parameteic ReLU (PReLU)

$$max(ax, x)$$

- $a$ is learned via backpropagation

## Exponential LU (ELU)

$$a(e^x-1) (x < 0)$$

- Vanishing gradient problem
- Zero-centered

## Maxout neuron

$$max(w_1x+b_1, w_2x+b_2)$$

- Generalization of ReLU
- Requires two sets of weights and biases

