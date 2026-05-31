# Artificial Intelligence, Machine Learning, and Deep Learning

## Artificial Intelligence (AI)
- Broad ambition to create intelligent systems
- Initially used rule-based expert systems
- Rule-based systems struggled with complex, real-world variability

## Machine Learning (ML)
- A subset of AI
- Uses statistical patterns and data to learn without explicit programming
- Emerged to address limitations of rule-based systems
- Remains essential for:
  - Smaller datasets
  - Specific industry applications

## Deep Learning (DL)
- A specialized approach within ML
- Inspired by biological neurons
- Automatically extracts features from massive datasets
- Excels at intricate tasks like:
  - Image recognition
  - Speech recognition

## Key Takeaway
The progression represents a shift from **manual logic** to **automated representation learning** across AI → ML → DL.


# Types of Machine Learning
## Based on Learning Paradigm
1. **Supervised Learning**

<img src="./assets/CampusX - Types of Machine Learning for Beginners Types of Machine learning in Hindi Types of ML in Depth [81ymPYEtFOw - 717x403 - 7m22s].png" alt="Supervised Learning" width="500"/>

2. **Unsupervised Learning**

<img src="./assets/CampusX - Types of Machine Learning for Beginners Types of Machine learning in Hindi Types of ML in Depth [81ymPYEtFOw - 734x413 - 19m30s].png" alt="Unsupervised Learning" width="500"/>

others:
<img src="./assets/CampusX - Types of Machine Learning for Beginners Types of Machine learning in Hindi Types of ML in Depth [81ymPYEtFOw - 734x413 - 23m34s].png" alt="Other Types of Machine Learning" width="500"/>

## Based on Training Method
1. **Batch Learning/offline learning**
- Trained on the entire dataset at once in Offline local system rather than in production environment
- Cannot adapt to new data without retraining

2. **Online Learning**
- Trained incrementally as new data arrives
- Can adapt to changing data patterns over time
- it gets trained and learn data and prediction in production environment
- libraries: Vowpal Wabbit, River, scikit-multiflow

## Based on learning approach
1. **Instance-based Learning**
- Stores training data and makes predictions based on similarity(memorizing) to new instances
- Examples: k-Nearest Neighbors (k-NN), Support Vector Machines (SVM)

2. **Model-based Learning**
- Builds a model from training data and uses it for predictions by internal logic(behavior)
- Examples: Linear Regression, Decision Trees, Neural Networks

<img src="./assets/image.png" alt="Instance-based vs Model-based Learning" width="500"/>

---
# Challenges in Machine Learning
1. Data Collection
2. insufficient data/Labelled Data
3. Non representative data (sampling noise/bias)
4. Data Quality
5. Overfitting (imp)
6. Underfitting
7. irrelevant features (garbage in garbage out)
8. Software Integration
9. Deployment and Maintenance
10. cost involved in training and deploying models

# Machine Learning Development Lifecycle (MLDL)
1. Problem Definition
2. Data Collection
3. Data Preprocessing (removing noise, handling missing values, encoding categorical variables)
4. Exploratory Data Analysis (EDA: understanding data distribution, identifying patterns, visualizing relationships)
5. Feature Engineering (creating new features, selecting relevant features)
6. Model Training, Evaluation, and Selection
7. Model Deployment
8. Testing (A/B testing, monitoring performance)
9. Optimization and Maintenance (retraining, updating models as needed)