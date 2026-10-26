# 🌸 Iris Flower Classification Using Decision Tree

## 📌 Project Overview
This project uses a Decision Tree Classification algorithm to classify Iris flowers into three species: Setosa, Versicolor, and Virginica.

The model is built using Python and Scikit-learn. It uses petal length and petal width as input features.

## 🛠️ Technologies Used
- Python
- Scikit-learn
- NumPy
- Jupyter Notebook

## 📊 Dataset
The Iris dataset is loaded directly from `sklearn.datasets`.

- **Total samples:** 150
- **Input features used:** Petal length and petal width
- **Target classes:** Setosa, Versicolor, Virginica

## ⚙️ Project Workflow
1. Load the Iris dataset.
2. Select petal length and petal width.
3. Split the dataset into training and testing sets.
4. Train the Decision Tree Classifier.
5. Make predictions on flower samples.
6. Evaluate the model using cross-validation, a confusion matrix, precision, and accuracy.

## 🤖 Model Configuration
- **Algorithm:** Decision Tree Classifier
- **Maximum depth:** 2
- **Training samples:** 120
- **Testing samples:** 30

## 📈 Model Evaluation Results

| Evaluation Metric | Score |
|---|---:|
| Cross-validation accuracy (2-fold) | 95.00% |
| Macro precision | 95.33% |
| Training accuracy | 95.83% |
| Test accuracy | 96.67% |

The model correctly classified **29 out of 30 test samples**.

## 🔮 Sample Prediction
The model can predict the Iris species using petal length and petal width.

The target labels represent:
- `0` — Setosa
- `1` — Versicolor
- `2` — Virginica

## 🚀 How to Run the Project
1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install scikit-learn numpy notebook
   ```

3. Open `Iris_Decision_Tree.ipynb` in Jupyter Notebook.
4. Run the notebook cells in order.

## ✅ Conclusion
The Decision Tree Classifier achieved **96.67% test accuracy** on the Iris dataset.

This project demonstrates the basic machine learning workflow, including data preparation, model training, predictions, and performance evaluation.
