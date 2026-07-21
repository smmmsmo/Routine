# Deep Learning

## Neural Network Foundations

- Perceptrons, multilayer perceptrons, universal approximation intuition
- Linear layers, activations, logits, probabilities, and decision boundaries
- Sigmoid, tanh, ReLU, Leaky ReLU, GELU, softmax
- MSE, binary cross-entropy, multiclass cross-entropy, contrastive losses
- Forward propagation, computational graphs, automatic differentiation, and backpropagation
- Parameter initialization: Xavier/Glorot, He initialization
- Batch, layer, group, and instance normalization concepts
- Dropout, weight decay, early stopping, data augmentation, and label smoothing
- SGD, momentum, Adam/AdamW, schedules, warmup, clipping, and mixed precision

## PyTorch Skills

- Tensors, shapes, broadcasting, devices, dtypes, and autograd
- `Dataset`, `DataLoader`, samplers, transforms, and reproducible splitting
- `nn.Module`, custom layers, losses, optimizers, schedulers, and initialization
- Training/validation loops, gradient accumulation, checkpoints, and inference
- Debugging NaNs, exploding/vanishing gradients, dead activations, and data bottlenecks
- TensorBoard or Weights & Biases concepts for experiment tracking
- GPU memory management, mixed precision, profiling, and distributed-training basics

## Architectures to Understand

- MLPs and residual MLPs
- Convolutional networks
- Recurrent networks, LSTMs, and GRUs
- Autoencoders
- Attention and transformers
- Graph neural network basics

## Required Implementations

1. Two-layer neural network using NumPy only
2. Backpropagation with numerical gradient checking
3. PyTorch classifier with configurable training loop
4. Learning-rate and regularization comparison
5. Checkpointed inference script with tests

## Projects

- Fashion-MNIST or CIFAR classifier
- Tabular neural network compared against boosted trees
- Autoencoder for denoising or anomaly detection
- Reusable PyTorch project template

## Mastery Checklist

- [ ] I can derive backpropagation for a small network.
- [ ] I understand activation/loss pairings.
- [ ] I can diagnose optimization from learning curves.
- [ ] I can write a complete PyTorch training pipeline.
- [ ] I understand regularization and normalization trade-offs.
- [ ] I can save, load, evaluate, and serve a model reproducibly.
