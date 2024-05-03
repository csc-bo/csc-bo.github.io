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
        2. **Forward Propagation**:

            or foward pass refers to the calculation and storage of intermediate variables (including outputs) for a neural network in order from the input to the output layer.

        2. Dense Layer: all inputs area densely connected to all outputs.
        3. What does it do?
            * Essentially, a perceptron learns a linear decision boundary that separates the input space into two regions, each corresponding to a different class.
            * **One perceptron**: Draws a line to separate data. binary classification.
            * **Multiple perceptrons** in layers: Can create complex curves and shapes to separate data

    - The Neural Networks
        1. Neural Network: Stacking Perceptrons to form neural network
            ![alt text](/MIT6.S191/SLNN.png)
            * -> MLP: Multi Layer Perceptron
        2. **Loss**: The **loss** of our network measures the cost incurred from incorrect predictions
            * Empirical Loss
                $$
                L_e(f) = \frac{1}{n} \sum_{i=1}^{n} L(y_i, f(x_i))
                $$
            * Cross Entropy Loos
                $$
                L(y, p) = - (y * log(p) + (1 - y) * log(1 - p))
                $$
            * Mean Squared Error Loss
                $$
                L(y, \hat{y}) = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2
                $$
        3. **Gradient Descent**
            1. **Backpropagation**: 

                Backpropagation is the application of gradient descent in deep learning, used to compute gradients of weights in neural networks. It employs the **chain rule** from calculus to efficiently propagate errors backwards, guiding updates to each layer's parameters. By calculating the partial derivatives of the loss function with respect to every weight, it determines how each weight should be adjusted to minimize the loss.

            4. Algorithm
                
                <!-- **1. Initialize Parameters**: Initialize the model's learnable parameters $ \theta $ (weights and biases) with random values or zeros.

                **2. Forward Propagation**: Compute the predicted output $ \hat{y} $ using the current parameters $ \theta $ and input data $ \hat{y} = f (\theta, x) $ where $ f $ represents the model's activation functions.

                **3. Calculate Loss**: Measure the difference between the predicted output and the true target $ y $ using a loss function $L = L(\hat{y}, y) ]$

                **4. Backward Propagation (Gradient Computation)**: Using the **chain rule**, compute the gradient of the loss function with respect to each parameter $( \theta_i ): [ \frac{\partial L}{\partial \theta_i} ]$

                **4. Update Parameters**: Perform a parameter update using the computed gradients and a learning rate $( \alpha ): [ \theta_i \leftarrow \theta_i - \alpha \cdot \frac{\partial L}{\partial \theta_i} ]$ The learning rate determines the step size at each iteration.

                **5. Iteration**: Repeat steps 2-5 for a fixed number of iterations or until a convergence criterion is met (e.g., reaching a specific loss threshold or a small change in the gradient).  -->

            4. **Learning Rate**

                Momentum or Adaptive Learning Rates: For improved convergence, incorporate momentum or adaptive learning rate techniques like Nesterov Accelerated Gradient (NAG), RMSprop, or Adam.

            4. **Mini-Batch Gradient Descent**

                Instead of using all data points at once, use a mini-batch of 

                $( B ) samples: [ \theta_i \leftarrow \theta_i - \frac{\alpha}{B} \sum_{j=1}^{B} \frac{\partial L_j}{\partial \theta_i} ]$

                $ where ( L_j )$ is the loss for the $( j )-th$ sample in the mini-batch.

            3. Optimization Algorithm
                * SGD(Stochastic Gradient Descent)
                * Adam
                * Adadelta
                * Adagrad
                * RMSProp


        
    - Real World Technique
        1. Mini-batches
        2. Fitting
            * underfitting: Model does not have capacity to fully learn the data
            * ideal fit
            * overfitting: Too complex, extra parameters, does not generalize well
        3. Regularization
            1. Dropout
                * During training, randomly set some activations to 0
                    * Typically 'drop' 50% of activations in layer
                    * Forces network to not rely on any 1 node
            
            2. Early Stopping

                * Stop training before we have a chance to overfit

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
