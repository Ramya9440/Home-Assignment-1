CS5720 Neural Networks and Deep Learning: Home Assignment 1

University of Central Missouri


Department of Computer Science & Cybersecurity

Summer 2025


👤 Student Information

Name: Thadikonda Ramya

Student id: 700762981

Course: CS5720 Neural Networks and Deep Learning

Instructor: I Hua Tsai 

Semester: Summer 2025
🧠 Task 1: Tensor Manipulations & Reshaping
**Objective:** Perform basic tensor operations such as reshaping, transposing, and broadcasting using TensorFlow.
**Steps:**
- Create a random tensor of shape (4, 6).
- Use TensorFlow to print its rank and shape.
- Reshape the tensor to (2, 3, 4).
- Transpose the reshaped tensor to (3, 2, 4).
- Create a smaller tensor of shape (1, 4) and broadcast it to the larger tensor, then add them.
- Explain broadcasting in TensorFlow.
**Expected Output:**
- Printed rank and shape before and after reshaping/transposing.
- Result of tensor addition using broadcasting.
- Explanation of broadcasting: TensorFlow automatically adjusts shapes to allow element-wise operations without explicitly reshaping.
📉 Task 2: Loss Functions & Hyperparameter Tuning
**Objective:** Compute and compare different loss functions to understand model sensitivity to prediction changes.
**Steps:**
- Define true labels (`y_true`) and predicted values (`y_pred`).
- Compute Mean Squared Error (MSE).
- Compute Categorical Cross-Entropy (CCE).
- Slightly change predictions and observe how the losses change.
- Plot the loss values using Matplotlib.
**Expected Output:**
- Printout of loss values before and after modifying predictions.
- Bar chart comparing MSE and CCE values.
🧮 Task 3: Train a Neural Network and Log to TensorBoard
**Objective:** Train a neural network on MNIST dataset and analyze model performance using TensorBoard.
**Steps:**
- Load and preprocess the MNIST dataset.
- Create and compile a simple neural network model.
- Train the model for 5 epochs.
- Log training using TensorBoard (`logs/fit/` directory).
- Launch TensorBoard to visualize training and validation metrics.
**Expected Output:**
- TensorBoard graphs for training vs. validation accuracy and loss.
- Log files in `logs/fit/`.

