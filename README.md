# 🌱 Smart Farming

Smart Farming is an ongoing agriculture-focused project that uses **Machine Learning and Deep Learning** to develop practical solutions for different farming-related problems.

The project is being developed step by step, with multiple modules planned to work together as a complete Smart Farming solution.

---

## 🚜 Current Modules

### 🌾 1. Crop Recommendation

A Machine Learning based system that recommends the most suitable crop based on soil and environmental conditions.

### Input Parameters

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- Soil pH
- Rainfall

### Model Used

- Random Forest Classifier
- Hyperparameter tuning using GridSearchCV
- Cross-validation
- Model evaluation using accuracy, classification report and confusion matrix

The model achieved approximately **99%+ accuracy** on the available dataset.

---

### 🌿 2. Weed Classification

A Deep Learning based system for identifying different weed species from images.

### Model Used

- EfficientNetB0
- Transfer Learning with ImageNet
- Data Augmentation
- Dropout
- Batch Normalization
- Early Stopping
- Learning Rate Reduction

The project includes image preprocessing, training, validation, testing, classification reports and confusion matrix analysis.

---

## 🔄 Currently In Progress

The Smart Farming project is actively being expanded with new modules.

### 🐛 Pest Identification

Currently working on developing a Deep Learning based pest identification system that can identify agricultural pests from images.

The planned system will:

- Accept an image as input
- Identify the pest
- Provide the predicted pest class
- Display prediction confidence
- Evaluate the model across multiple pest classes

---

### 💰 Cost Estimation

Another module currently being planned/developed is **crop cultivation cost estimation**.

The system will aim to estimate the approximate cost of cultivating a crop based on factors such as:

- Crop type
- Land area
- Seeds
- Fertilizers
- Labour
- Irrigation
- Pesticides
- Machinery
- Other farming expenses

The goal is to provide farmers with an approximate idea of the investment required for cultivation.

---

## 🔮 Future Plans

After completing the current modules, the project will be further expanded to:

- Complete Pest Identification
- Complete Cost Estimation
- Integrate Crop Recommendation, Weed Classification, Pest Identification and Cost Estimation
- Improve model performance and reliability
- Add more agricultural datasets and use cases
- Build a user-friendly web interface
- Develop a dedicated **Smart Farming portfolio website** to showcase the complete project, models, results and future work

---

## 🛠️ Technologies Used

### Machine Learning
- Python
- Pandas
- NumPy
- Scikit-learn
- Random Forest
- GridSearchCV

### Deep Learning
- TensorFlow
- Keras
- EfficientNetB0
- Transfer Learning

### Data Analysis & Visualization
- Matplotlib
- Seaborn

### Development
- Jupyter Notebook
- Google Colab
- VS Code
- Git
- GitHub

---

## 📁 Project Structure

```text
smart-farming/
│
├── crop-recommendation/
│   └── crop_recommendation.ipynb
│
├── weed-classification/
│   └── weed_classification.ipynb
│
├── README.md
└── .gitignore
```
## 📊 Project Status

| Module | Status |
|---|---|
| 🌾 Crop Recommendation | ✅ Completed |
| 🌿 Weed Classification | ✅ Completed |
| 🐛 Pest Identification | 🔄 In Progress |
| 💰 Cost Estimation | 🔄 In Progress |
| 🌐 Smart Farming Website | 📌 Planned |

---

## 👨‍💻 Author

**Himanshu Chaudhary**  

---

> 🚧 **Smart Farming is an ongoing project and is continuously being improved with new models, features and agricultural use cases.**
