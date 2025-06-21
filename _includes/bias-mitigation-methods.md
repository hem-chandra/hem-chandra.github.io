We are increasingly using machine learning (ML) software to make autonomous decisions such as identifying credit risks, criminal sentencing, discharging patients, predicting heart diseases, hiring employees, and more. However, biased decisions made by ML software against specific social groups—often based on protected or sensitive attributes (e.g., sex)—have raised significant concerns within both the software engineering (SE) and ML communities.

**ML software learns its decision logic from training data. As a result, if the training data is biased, the model can learn and perpetuate those biases in its predictions.**

---

### Bias Mitigation Approaches in ML-Based Software

Bias mitigation methods in ML-based software are broadly classified into three categories:

#### 1. Pre-processing Methods
These methods work on the **training data** before the model is built. Techniques include reweighting, data transformation, label correction, or generating synthetic data to reduce or eliminate bias from the dataset itself.

#### 2. In-processing Methods
In this approach, bias is addressed **during model training**. It often involves modifying the learning algorithm, incorporating fairness constraints or custom loss functions. The dataset is typically divided into training, validation, and testing subsets:
- **Training**: Used to train the model.
- **Validation**: Used for hyperparameter tuning or bias-aware optimization.
- **Testing**: Used for final model evaluation.

#### 3. Post-processing Methods
These techniques operate **after the model has been trained**. They do not modify the model itself but instead adjust its predictions to mitigate bias. Methods include output relabeling, threshold adjustments, or calibration to ensure fairness in the final decision-making.

---

