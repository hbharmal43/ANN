# **Artificial Neural Network** 🧠

## **About the Project**
This project is an **Artificial Neural Network (ANN)** implemented in **Python** as part of my honors contract project. The goal was to understand the fundamentals of **machine learning** and neural networks by building one from scratch.  

By creating this project, I gained insight into **how neural networks function internally**, including **weight initialization, forward propagation, backpropagation, and gradient descent**.

---

## **Why I Chose This Project**
I wanted to explore **machine learning** and understand **what really happens inside a neural network** at a fundamental level. This project helped me achieve a **surface-level understanding** by implementing a simple neural network from scratch.

---

## **Technologies & Libraries Used** 📚
- **Python** 🐍 – Primary programming language
- **NumPy** – For numerical computations with arrays and matrices
- **Pandas** – For data manipulation and analysis
- **Matplotlib** – For visualizing results with various plots

---

## **Key Functions & Their Roles** ⚙️

### **Neural Network Initialization**
- `init_params()`: Initializes the weights and biases for a two-layer neural network.

### **Activation Functions**
- `ReLU(Z)`: Implements the **Rectified Linear Unit (ReLU)**, a common non-linear activation function.
- `softmax(Z)`: Normalizes the output using the **softmax function**.

### **Forward & Backward Propagation**
- `forward_prop()`: Moves data from the **input layer** to the **output layer**.
- `backward_prop()`: Propagates the **total loss** back into the neural network to adjust weights.

### **Gradient Descent & Parameter Updates**
- `ReLU_deriv(Z)`: Computes the derivative of the **ReLU activation function**.
- `One_hot()`: Converts class labels into a **one-hot encoded matrix**.
- `update_params()`: Updates the weights and biases using the computed gradients.
- `gradient_descent()`: Implements the **gradient descent** algorithm to train the neural network over multiple iterations.

---

## **How It Works** 🚀
1. **Initialize parameters** (weights and biases).
2. **Feedforward step** using activation functions.
3. **Compute loss** and track error.
4. **Backpropagate errors** through the network.
5. **Update weights** using gradient descent.
6. **Repeat the process** over multiple iterations to minimize error.

---

## **Resources Used** 📖
I referred to the following resources to understand and implement the concepts in this project:

1. **Neural Networks from Scratch in Python** – Sentdex *(YouTube Playlist)*  
   📺 [Watch Here](https://www.youtube.com/playlist?list=PLQVvvaa0QuDcjD5BAw2DxE6OF2tius3V3)  

2. **Building a Neural Network from Scratch**  
   📺 [Watch Here](https://www.youtube.com/watch?v=w8yWXqWQYmU&t=219s)  

3. **What is a Neural Network?**  
   📺 [Watch Here](https://www.youtube.com/watch?v=ER2It2mIagI)  

4. **Make Your Own Neural Network – Book by Tariq Rashid**  
   📚 [Buy Here](https://www.amazon.com/Make-Your-Own-Neural-Network/dp/1530826608/)  

---

## **How to Run the Project** 💻
### **Prerequisites**
Ensure you have **Python 3.x** installed along with the required libraries.

---

### **Installation**
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-github-username/artificial-neural-network.git
   cd artificial-neural-network
Install dependencies

  ```bash
    pip install numpy pandas matplotlib
    python neural_network.py
