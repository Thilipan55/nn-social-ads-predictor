# Neural Network: Social Network Ad Purchase Predictor

This is a beginner-friendly **machine learning project** that uses a **Multilayer Perceptron (MLP)** to predict whether a user will purchase a product based on their **age** and **estimated salary**. Built using **Keras (TensorFlow 2.x)** and trained on the **Social_Network_Ads.csv** dataset.

---

## Dataset

The dataset contains:
- `Age` (int)
- `EstimatedSalary` (int)
- `Purchased` (0 = No, 1 = Yes)

### Source:
Available publicly, often used for classification demos.

---

##  What This Project Covers

- Data preprocessing with `StandardScaler`
- Graphical data visualization using `matplotlib`
- A fully functional neural network (`Sequential`) with:
  - Input layer
  - Two hidden layers with ReLU
  - Output layer with sigmoid activation
- Train/test split and performance evaluation
- **Interactive user input** for live predictions

---

## Model Architecture

- **Type**: Multilayer Perceptron (MLP)
- **Input**: 2 features (age, salary)
- **Hidden layers**: Customizable — currently using 2 layers
- **Output**: Probability of purchase (0–1)

---

##  Example Prediction

```bash
Enter Age: 42
Enter Estimated Salary: 80000
Prediction: Likely to Purchase (87.6% confidence)
