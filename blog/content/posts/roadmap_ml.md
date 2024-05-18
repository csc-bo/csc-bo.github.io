+++
title = 'Roadmap for machine lerning'
date = 2024-05-02T12:14:51+08:00
draft = false
+++

# Machine Learning

## Courses

### UofT

- [x] MAT334 Complex Variables
- [x] MAT223&MAT224 Linear Algebra I&II
- [x] MAT236 Vector Calculus
- [x] STA302H1/STA1001: Methods of Data Analysis I

### MIT

- [x] 6.S191 Introduction to Deep Learning
    - [x] Sequence to Sequence
    - [x] Computer Vision
    - [x] Reinforcement Learning
    - [x] Generative Modeling
    - [x] Lab 1:
        Tensorflow, Tensor, Auto differentiation, GradientTape, RNN
    - [x] Lab 2:
        MNIST, CNN, VAEs, Debiasing Facial Detection
    - [ ] extra lab
        - [ ] llm finetune
        - [ ] self driving

### Standford
1. Artificial Intelligence
a. **CS 221**
b. At least four of: CS 223A, **224N**, 224S, **224U**, 224V, **224W**, 228, **229**, 231A, **231N**, **234**, 237A, 237B, 238
c. A total of at least 21 units from (a), (b) and the following: CS 205L, 224R, 225A, 227B, 229M, 230, 233, 
235, **236**, 239, 246, 257, 270, 271, 273A, 273B, 274, 275, 279, 281, 322, 324, 325B, 326, 327A, 329, **330**, 
331B, 332, 333, 345, 348N, 361, 368, 371, 375, 377**, 379**, 398, 399**, 428A, 428B, 432; EE 263, 276, 
278, 364A, 364B, 378B; ENGR 205, 209A; MS&E 226, 252; PSYCH 209; STATS 202, 315A, 315B
#### [ ] CS229(Required): Machine Learning
#### [ ] CS231n: Deep Learning for Computer Vision
##### Assignments
- [ ] Assignment #1
Image Classification, kNN, SVM, Softmax, Fully Connected Neural Network
- [ ] Assignment #2
Fully Connected and Convolutional Nets, Batch Normalization, Dropout, Pytorch & Network Visualization
- [ ] Assignment #3
Image Captioning with RNNs and Transformers, Network Visualization, Generative Adversarial Networks, Self-Supervised Contrastive Learning
- [x] Lecture 1: Computer vision overview
##### Deep Learning Basics
- [x] **Lecture 2: Image Classification with linear Classifiers**
    - [x] The data-driven approch
    - [x] K-nearest neighbor
    - [x] Linear classifiers
    - [x] Algebraic/Visual/ Geometric veiwpoints
    - [x] SVM and Softmax loss
- [ ] **Lecture 3: Regularization and Optimization**
    - [x] Regularization
    - [x] Stochastic Gradient Descent
    - [x] Momentum, AdaGrad, Adam
    - [x] Learning rate schedules
- [ ] **Lecture 4: Neural Networks and Backpropagation**
    - [x] Multi-layer Perceptron
    - [x] Backpropagation
##### Perceiving and Understanding the Visual World
- [ ] **Lecture 5: Image Classification with CNNs**
    - [x] History
    - [x] Higher-level representations, image features
    - [x] Convolution and pooling
- [ ] **Lecture 6: CNN Architectures**
    - [x] Batch Normalization
    - [x] Transfer learning
    - [x] AlexNet, VGG, GoogLeNet, ResNet
- [ ] **Lecture 7: Recurrent Neural Networks**
    - [x] RNN, LSTM, GRU
    - [x] Language modeling
    - [x] Image captioning
    - [x] Sequence-to-sequence
- [ ] **Lecture 8: Attention and Transformers**
    - [x] Self-Attention
    - [x] Transformers
- [ ] **Lecture 9: Object Detection and Image Segmentation**
    - [ ] Single-stage detectors
    - [ ] Two-stage detectors
    - [ ] Semantic/Instance/Panoptic segmentation
- [ ] **Lecture 10: Video Understanding**
    - [x] Video classification
    - [x] 3D CNNs
    - [x] Two-stream networks
    - [ ] Multimodal video understanding
- [ ] **Lecture 11: Visualizing and Understanding**
    - [ ] Feature visualization and inversion
    - [ ] Adversarial examples
    - [ ] DeepDream and style transfer
##### Generative and Interactive Visual Intelligence
- [ ] **Lecture 12: Self-supervised Learning**
    - [ ] Pretext tasks
    - [ ] Contrastive learning
    - [ ] Multisensory supervision
- [ ] **Lecture 13: Generative Models**
    - [x] Generative Adversarial Network
    - [ ] Diffusion models
    - [x] Autoregressive models
- [ ] **Lecture 14: OpenAI Sora**
    - [ ] Diffusion models
- [ ] **Lecture 15: Robot Learning**
    - [ ] Deep Reinforcement Learning
    - [ ] Model Learning
    - [ ] Robotic Manipulation
- [ ] **Lecture 16: Human-Centered Artificial Intelligence**
- [ ] **Lecture 17: Guest Lecture by Prof. Serena Yeung-Levy**
- [ ] **Lecture 18: 3D Vision**
    - [ ] 3D shape representations
    - [ ] Shape reconstruction
    - [ ] Neural implicit representations
#### [ ] CS236(*)： Deep Generative Models
#### [ ] CS330(*): Deep Multi-Task and Meta Learning
#### [ ] CS234(*): Reinforcement Learning
#### [ ] CS224n(*): Natural Language Processing with Deep Learning
#### [ ] CS224u(*): Natural Language Understanding
#### [ ] CS224w(*): Machine Learning with Graphs
#### [ ] CS237a: Principles of Robot Autonomy I
#### [ ] CS237b: Principles of Robot Autonomy II
#### [ ] CS326: Topics in Advanced Robotic Manipulation
#### [ ] CS336: Language Modeling from Scratch

### UCB
#### [ ] CS267 Application of Parallel Computers

## Online Resources

### [ ] Pytorch

- [x] freeCodeCamp: PyTorch for Deep Learning & Machine Learning
    - [x] Fundamentals: Tensor
        - [x] Exercise
    - [x] Workflow Fundamentals: Data, Model, Trainning, Inference, Save & Load Model
        - [x] Exercise
    - [x] Neural Network Classification: Binary, Multi-class, Multi-label
        - [x] Exercise
    - [x] Computer Vision: CNN
        - [x] Exercise
    - [ ] Custom Dataset
    - [ ] Going Modular
    - [ ] Transfer learning
    - [ ] Experiment Tracking
    - [ ] Paper Replicating
    - [ ] Model Deployment


- [x] StatQuest：Introduction to Pytorch
- [ ] Build a CNN detect handwrite aphabets
- [ ] RNN / LSTM
- [ ] Transformer
- [ ] ViT
- [ ] ...

### [ ] Neural Networks: Zero to Hero

1. [x] The spelled-out intro to neural networks and backpropagation: building micrograd
    - [x] micrograd exercise
2. [x] The spelled-out intro to language modeling: building makemore
3. [x] Building makemore Part 2: MLP
    - [ ] E1
    - [ ] E2
4. [ ] Building makemore Part 3: Activations & Gradients, BatchNorm
    - [ ] the forward pass activations, backward pass gradients
    - [ ] Batch Normalization
    - [ ] typical diagnostic tools and visualizations
    - [ ] Residual connections and
    - [ ] the Adam optimizer
    - [ ] E1
    - [ ] E2
5. [ ] Building makemore Part 4: Becoming a Backprop Ninja
    - [ ] Exercise 1
    - [ ] Exercise 2
    - [ ] Exercise 3
    - [ ] Exercise 4
6. [ ] Building makemore Part 5: Building a WaveNet
7. [ ] Let's build GPT: from scratch, in code, spelled out.
8. [ ] Let's build the GPT Tokenizer
- [x] Neural Networks by 3Blue1Brown
    - [x] Neural Networks and Deep Learning
    - [x] Gradient Descent, How machines learn
    - [x] Backpropagation
    - [x] Backpropagation Calculus
    - [x] GPT(Generative Pre-trained Transformer)
- [ ] Essence of linear algebra
    review my linear algebra
- [ ] Essence of calculus
    review my calculus

## Fun Projects

### Stock Trend/Pricing Prediction

- [ ] LSTM
- [ ] Tranformer
- [ ] MultiModel

### Face reconginition

- [ ] CNN
