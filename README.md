
# Concrete Strength Prediction with Keras  
This repository contains a regression project using a neural network built with Keras to predict the compressive strength of concrete based on its composition and curing time.  

## Features  
- **Dataset**: Contains observations of concrete mix components and their compressive strength.  
  - **Cement**  
  - **Blast Furnace Slag**  
  - **Fly Ash**  
  - **Water**  
  - **Superplasticizer**  
  - **Coarse Aggregate**  
  - **Fine Aggregate**  
  - **Age (in days)**  
  - **Strength (target)**  

- **Regression Algorithm**:  
  - Deep Neural Network (DNN) using Keras and TensorFlow.  

- **Metrics for Evaluation**:  
  - Mean Absolute Error (MAE)  
  - Mean Squared Error (MSE)  
  - R² Score  

## Project Workflow  
1. **Data Preprocessing**:  
   - Normalization of input features to improve training efficiency.  
   - Train-test split (80% training, 20% testing).  

2. **Model Building**:  
   - Fully connected feedforward neural network with multiple hidden layers.  
   - ReLU activation for hidden layers and linear activation for the output layer.  
   - Mean Squared Error as the loss function and Adam optimizer.  

3. **Training**:  
   - Train the model using the training data for multiple epochs.  
   - Monitor loss and validation metrics during training.  

4. **Evaluation**:  
   - Evaluate the model's performance on the test data.  
   - Generate predictions and compare them with actual values.  



## Requirements  
- Python 3.8+  
- TensorFlow/Keras  
- Required libraries:  
  ```bash
  pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
  ```  
