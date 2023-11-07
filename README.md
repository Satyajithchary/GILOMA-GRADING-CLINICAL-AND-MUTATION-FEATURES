# Giloma-Grading-Clinical-and-Mutation-Features

**🧠 Machine Learning for Tumor Classification in Brain Cancer 🚀**

**Introduction:**
Embark on a data-driven journey into brain cancer classification! 🌐 This project leverages a diverse set of machine learning algorithms to predict tumor classes based on unique genomic features. The dataset, sourced from TCGA, encompasses a range of clinical and genetic attributes.

**Methods:**
1. **Data Preprocessing:** Loaded and cleaned the dataset using pandas, addressing missing values and encoding categorical variables. 🧹
2. **Exploratory Data Analysis (EDA):** Explored the dataset's characteristics and relationships using seaborn, visually representing tumor grades with respect to gender and race. 📊
3. **Feature Encoding:** Utilized Label Encoding for preprocessing, transforming categorical variables into numerical representations. 🔄
4. **Model Training:** Employed various classifiers, including Perceptron, Logistic Regression, Decision Trees, SVM, and K-Nearest Neighbors. 🤖
5. **Model Evaluation:** Assessed model performance using accuracy scores on training and testing sets. 📈
6. **Hyperparameter Tuning:** Conducted a grid search for optimal hyperparameters using SVM, enhancing model accuracy. 🎛️

**Results:**
1. **Perceptron:**
   - Training Accuracy: 94.6%
   - Testing Accuracy: 91.9% 🎯

2. **Logistic Regression:**
   - Training Accuracy: 99.6%
   - Testing Accuracy: 98.5% 🚀

3. **Decision Trees:**
   - Training Accuracy: 100%
   - Testing Accuracy: 99.3% 🌳

4. **SVM:**
   - Training Accuracy: 98.4%
   - Testing Accuracy: 97.5% 🌐

5. **K-Nearest Neighbors:**
   - Optimal k: 1
   - Testing Accuracy: 97.8% 🤝

6. **Hyperparameter Tuning (SVM):**
   - Best Model: SVM with C=5, degree=6, and kernel=linear.
   - Achieved Testing Accuracy: 99.0% 🚀

**Conclusion:**
This project showcases the efficacy of machine learning in brain cancer classification. Logistic Regression and Decision Trees emerged as top-performing models, demonstrating high accuracy. The SVM model, optimized through hyperparameter tuning, further improved accuracy. The findings contribute to the ongoing efforts in leveraging data-driven approaches for cancer diagnosis and classification. 🧠💻🚀
