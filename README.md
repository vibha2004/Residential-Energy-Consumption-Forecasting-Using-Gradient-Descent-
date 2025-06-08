
# 🔌 Energy Consumption Prediction Based on Outside Temperature

## 📘 Overview

This project aims to **predict household energy consumption** based on the **outside temperature**, using two different machine learning approaches:

1. A **custom neural network implementation** built from scratch in Python.
2. A **TensorFlow-based neural network model** for comparison.

The project demonstrates the impact of temperature on energy consumption and aims to help **utility companies**, **researchers**, and **environmental planners** optimize energy management and anticipate peak loads efficiently.

---

## 🧠 Methodology

### 📊 Data

* **Type**: Synthetic or real-world data with two columns:

  * `Outside Temperature (°C)`
  * `Energy Consumption (kWh)`
* **Preprocessing**:

  * Normalization for neural network input.
  * Splitting into training and testing datasets.

### 🛠️ Model 1: Custom Neural Network

* Implemented using **NumPy** without any external libraries.
* Based on **Logistic Regression** with a single neuron.
* Uses **Gradient Descent** to minimize loss.
* Components:

  * Forward propagation
  * Cost function (Binary Cross-Entropy)
  * Backpropagation
  * Parameter updates

### ⚙️ Model 2: TensorFlow Neural Network

* Implemented using the **Keras API**.
* Comprises:

  * Input layer
  * Dense hidden layers
  * Output layer with activation
* Trained using built-in optimizers and loss functions.

### 🔍 Evaluation Metrics

* **Loss curves**
* **Prediction vs. Ground Truth**
* **Training accuracy**

---

## 📂 File Structure

```
📁 Energy-Prediction/
│
├── Final (1).ipynb                # Main Jupyter notebook with complete code
├── data_hourly.csv         # Data file with temperature and consumption values
├── README.md                      # Project documentation (this file)
```

---

## 🔧 How to Run

### ✅ Requirements

```bash
pip install numpy pandas matplotlib tensorflow
```

### ▶️ Running the Notebook

1. Open `Final (1).ipynb` using Jupyter Notebook or JupyterLab.
2. Run each cell sequentially:

   * The first section demonstrates the custom implementation.
   * The second section implements the TensorFlow model.
3. Observe training progress and compare predictions.

---

## 📉 Results

* The **custom model** provides insight into the internal workings of neural networks.
* The **TensorFlow model** typically achieves faster convergence and better performance due to advanced optimization techniques.
* Visualization shows a clear **correlation between outside temperature and energy usage**.

---

## 🔍 Applications

* **Smart Grids**: Predict energy demand during seasonal changes.
* **Building Management Systems**: Optimize HVAC usage.
* **Environmental Research**: Understand how climate affects energy patterns.
* **Educational Tool**: Demonstrates core ML concepts through hands-on coding.


---

**Residential Energy Consumption Forecasting - Optimizing Energy Usage Through Machine Learning** ⚡📊🏠
