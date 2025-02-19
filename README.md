
# DietRecommendationSystem_ML_Project

# 🍎 **Diet Recommendation System**

This repository contains the implementation of a **Diet Recommendation System** designed to help users achieve their dietary goals—whether it's maintaining a healthy lifestyle, gaining weight, or losing weight. By leveraging advanced machine learning techniques and personalized user inputs, this system offers precise, user-centric food recommendations.

---

## 🚀 **Key Features**
- **Personalized Recommendations**: 
   - Users can input age, height, weight, and dietary preferences (e.g., Veg/Non-Veg).
   - Specific goals like *Healthy*, *Weight Gain*, or *Weight Loss* guide the recommendations.
- **Advanced Data Processing**: 
   - Integrates a refined dataset with detailed nutritional information, including:
     - Calories
     - Fats
     - Protein
     - Carbohydrates
     - Cholesterol
     - Sodium
     - Fiber
     - Sugar content
- **Machine Learning Techniques**: 
   - **Random Forest Classifier** predicts food items aligning with dietary needs.
   - **Cosine Similarity** matches nutritional profiles to user preferences for enhanced accuracy.
- **User-Friendly System**: Offers clear, actionable recommendations tailored to individual dietary needs.

---

## 📊 **Project Methodology**

### 1️⃣ **Data Preprocessing**
- Cleaned and refined a custom dataset for accuracy.
- Used **NLP techniques** (e.g., Spacy, NLTK) to process food descriptions and extract relevant nutritional details.
- Addressed challenges with stop words and important domain-specific terms to improve results.

### 2️⃣ **Model Development**
- **Content-Based Filtering**: Used TF-IDF and Cosine Similarity to recommend food items based on nutritional matching.
- **Collaborative Filtering**: Utilized user-item interactions to predict preferences.
- **Hybrid Model**: Combined Content-Based and Collaborative Filtering for robust recommendations.
- **Random Forest**: Employed for classification of food items based on user dietary goals.

### 3️⃣ **Model Evaluation**
- Metrics such as **Precision**, **Recall**, and **Accuracy** were used to assess the system's performance.

### 4️⃣ **Deployment**
- System deployed with user input features for live, personalized recommendations.

---

## 🛠 **Technologies Used**
- **Programming Language**: Python
- **Libraries**: NumPy, pandas, scikit-learn, NLTK, Spacy, Matplotlib
- **Platforms**:
   - Google Colab: For initial development and model training.
   - Google Cloud Platform: Used for high-memory tasks like data preprocessing and model training.

---

## 📂 **Dataset**
- **Source**: [FoodRecSys-V1 Dataset on Kaggle](https://www.kaggle.com/datasets/elisaxxygao/foodrecsysv1)
- **Details**:
  - Recipes with ingredients, cooking instructions, and nutritional information.
  - User-recipe interaction data for ratings and reviews.

---

## 🔑 **Key Challenges**
1. **Resource Constraints**: High memory requirements led to execution failures. 
   - **Solution**: Utilized Google Cloud Platform for enhanced processing capabilities.
2. **Data Preprocessing**:
   - Pretrained NLP models like Spacy removed essential domain-specific terms. 
   - **Solution**: Created a custom corpus of stop words for better preprocessing.
3. **Scalability**:
   - Integration of large datasets with efficient computation required cloud-based solutions.

---

## 📈 **Future Improvements**
1. Include additional nutritional factors like cholesterol and blood sugar levels.
2. Enhance diversity in recommendations through ingredient substitutions.
3. Develop a user-facing health management dashboard to monitor dietary habits.

---

## 📥 **Installation**

1. Clone the repository:

   git clone https://github.com/deekshitha2510/DietRecommendationSystem_ML_Project

