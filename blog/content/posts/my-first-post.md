+++
title = 'Notes for MIT 6.S191'
date = 2024-05-01T21:52:19+08:00
draft = false
+++

## 1. Introduction to Deep Learning

After watch one of Feifei Li and Geffery Hinton's video on Youtube, I start to gain interest in DeepLearning, then I found this MIT course online that is a very comprehensive introduction for the Deep Learning which perfect for beginners like myself. This blog post marks the beginning of my journey into the world of machine learning, serving as a collection for my course notes and insights from related materials.

## 2. Course Content

1. Introductin
    - The Perceptron
        1. Perceptron: Simplified
            ![alt text](/MIT6.S191/perceptron.png)
            * Activation Functions is to introduce **non-linearites** into the network
            * Sigmoid, Hyperbolic Tangent, Rectified Linear Unit(ReLU)
            * We can implement this graph on code very easily
        2. Dense Layer: all inputs area densely connected to all outputs.
        3. What does it do?
            * Essentially, a perceptron learns a linear decision boundary that separates the input space into two regions, each corresponding to a different class.
            * **One perceptron**: Draws a straight line to separate data.
            * **Multiple perceptrons** in layers: Can create complex curves and shapes to separate data

    - The Neural Networks
        1. Neural Network: Stacking Perceptrons to form neural network
            ![alt text](/MIT6.S191/SLNN.png)
            * -> MLP: Multi Layer Perceptron
        2. **Loss**: The loss of our network measures the cost incurred from incorrect predictions
            * Empirical Loss
            * Cross Entropy Loos
            * Mean Squared Error Loss
        3. **Gradient Descent**
            1. **Backpropagation**: chain rule
            2. Stochastic Gradient Descent
            3. Optimization Algorithm
                * SGD(Stochastic Gradient Descent)
                * Adam
                * Adadelta
                * Adagrad
                * RMSProp
        4. **Learning Rate**
        
    - Real World Technique
        1. Mini-batches
        2. Fitting
            * underfitting: Model does not have capacity to fully learn the data
            * ideal fit
            * overfitting: Too complex, extra parameters, does not generalize well
        3. Regularization
            1. Dropout
            2. Early Stopping

2. Deep Sequence Modeling
3. Deep Computer Vision
4. Deep Generative Modeling
5. Deep Reinforcement Learning
6. Limitation and New Frontiers

-  Module Summaries: Briefly summarize each module of the course, highlighting key concepts and algorithms covered.
-  Lecture Notes: You can include your personal notes from lectures, focusing on important points and areas of difficulty.
*  Assignments and Projects: Discuss the assignments and projects assigned in the course, sharing your approach and solutions.

## 3. Resources

- Share any additional resources you found helpful while taking the course, such as:

- Online Tutorials: Links to relevant online tutorials or articles that provide further explanation on specific topics.
- Research Papers: References to important research papers in the field of deep learning.
- Software Libraries: Information about deep learning libraries used in the course, such as TensorFlow or PyTorch. 
## 4. Personal Insights and Reflections

Share your personal thoughts and reflections on the course, including:

- Challenges Faced: Discuss any challenges you encountered while learning the material and how you overcame them.
- Key Takeaways: Highlight the most important things you learned from the course.
Future Applications: Explore potential applications of deep learning that you find interesting. 5. Conclusion

Conclude your post by summarizing your experience with the course and expressing your thoughts on the field of deep learning as a whole.
