----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
MACHINE LEARNING-ENHANCED INTRUSION DETECTION SYSTEM FOR ACCELERATED THREAT RESPONSE THROUGH FEATURE SPACE REDUCTION IN CRITICAL INFRASTRUCTURES
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Each folder contains:
- `README.md`: Detailed walkthrough
- Sample datasets (where allowed)
- Diagrams & flowcharts (embedded as images)

---

## 🔬 Experiment Modules

### 🔹 Experiment 1: EDA and Feature Engineering
Derived statistical and network-based features from raw log data to enhance detection granularity.

> 📍 **Output:** Ranked feature list with 50% reduction and improved model interpretability.

### 🔹 Experiment 2: Modeling
Trained multiple classifiers (Random Forest, Gradient Boost, XGBoost) to benchmark accuracy, training time, features used, confusion matrix, precision, and recall.

> 📍 **Output:** Selected Random Forest model with 99.22% test accuracy and minimum features used.

### 🔹 Experiment 3: Evaluation using 10-fold Cross-Validation
Stress-tested models against unseen threats and edge cases, analyzing confusion matrices and false positives.

> 📍 **Output:** ROC-AUC > 0.98 and consistent performance across all test splits.

---

## ⚙️ Application Modules

### 🔸 Application 1: Comparitive analysis of Feature selection and No Feature selection on complete Gas Pipeline Dataset
An interactive dashboard for visualizing anomalies and performance comparison across multiple classifiers.

> 📍 **Highlights:** Tabular logs, Impact of Feature Selection, threat score indicators.

### 🔸 Application 2: Evaluation of chosen ML classifiers for Gas Pipeline clusters
Recognized best approach from Feature engineering to ML classifier for each cluster.

> 📍 **Highlights:** Integrated feedback loop for model updating and alert prioritization.

---

## 📈 Flowcharts

To view pipeline flowcharts:

| Module        | Flowchart Preview |
|---------------|------------------|
| **Experiment 1** | ![Exp1 Flow](exp1_flowchart.png) |
| **Application 1** | ![App1 Flow](app1_flowchart.png) |
| **Application 2** | ![App2 Flow](app2_flowchart.png) |


---

## 📦 Requirements & Dependencies

Each folder includes a local `README.md` with its:
- Required Python libraries
- Dataset source and structure
- Execution instructions

---

## 📍 How to Reproduce (Without Code)

1. Follow the order: `Exp1 → App1 → App2`
2. Use individual `README.md` files for environment setup and data simulation
3. Replicate models using detailed hyperparameters and algorithm notes provided

---

## 📬 Contact

For research collaborations or implementation questions, feel free to connect:  
**Kritika Sharma**  
[LinkedIn](https://www.linkedin.com/in/kritika-sharma95/)  
📧 kritika.sharma.8495@gmail.com  