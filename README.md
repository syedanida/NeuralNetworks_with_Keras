# 🧠 Deep Learning Augmentation & Customization 

This repository is organized into two major parts:

1. **Data Augmentation & Generalization Techniques**
2. **Advanced Keras & TensorFlow Constructs**

---

## 🎥 Video Walkthrough

📌 [Watch the full walkthrough here](#)  

---

## 📚 Part 1: Data Augmentation & Generalization Techniques

In this part, we explore various augmentation strategies and generalization techniques using **TensorFlow**, **Keras**, **KerasCV**, **AugLy**, **NLPAug**, and **fastai**.

### ✅ Regularization Techniques (A/B tested)
- `l1`, `l2`, and combined regularization
- Dropout layers
- Early stopping and custom callbacks
- Monte Carlo Dropout (for uncertainty estimation)
- Various initializations (He, Glorot, etc.)
- Batch Normalization and custom dropout
- TensorBoard tracking
- Hyperparameter tuning using **Keras Tuner**

### ✅ Data Augmentation Domains
Each subdomain includes implementation using either TensorFlow, AugLy, or specialized libraries:

| Domain          | Colab Link |
|-----------------|------------|
| Image           | [Colab](#) |
| Video           | [Colab](#) |
| Text (NLP)      | [Colab](#) |
| Time Series     | [Colab](#) |
| Tabular Data    | [Colab](#) |
| Speech          | [Colab](#) |
| Document Images | [Colab](#) |
| fastai Augment  | [Colab](#) |

---

## ⚙️ Part 2: Advanced Keras Deep Learning Constructs

In this part, we dive deep into advanced TensorFlow & Keras customizations to get a firm grasp of how deep learning works under the hood.

### 🔧 Covered Concepts

| Concept | Description |
|--------|-------------|
| **Custom Learning Rate Scheduler** | Implemented OneCycleScheduler |
| **Custom Dropout** | Included MCAlphaDropout variant |
| **Custom Normalization** | Used MaxNormDense layer |
| **TensorBoard Integration** | For monitoring training progress |
| **Custom Loss Function** | Implemented HuberLoss |
| **Custom Activations & Initializers** | E.g., leaky_relu, my_glorot_initializer |
| **Custom Metrics** | HuberMetric |
| **Custom Layers** | e.g., AddGaussianNoise, LayerNormalization |
| **Custom Models** | ResidualRegressor, ResidualBlock |
| **Custom Optimizer** | Created MyMomentumOptimizer |
| **Custom Training Loop** | Full control over training logic (e.g., Fashion MNIST) |

👉 Check out the implementation:  
[Advanced Keras Constructs Colab Notebooks](#)


