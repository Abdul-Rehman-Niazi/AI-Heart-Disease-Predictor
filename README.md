# AI-Heart-Disease-Predictor
🫀 AI-powered Heart Disease Predictor using Machine Learning (Logistic Regression &amp; Random Forest) with user-friendly CSV input support.
Got it ✅ Thanks for sharing your code!
Here’s a **professional and attractive README.md draft** you can use for your GitHub repo:

---

# 🫀 AI Heart Disease Predictor

An end-to-end machine learning project that predicts the likelihood of heart disease based on patient health data.
This project uses **Logistic Regression** and **Random Forest Classifier** to analyze clinical features and provide accurate predictions, along with feature importance insights.

---

 📌 Features

* 📂 **Dataset:** UCI Heart Disease dataset (via Kaggle).
* 🧹 **Data Preprocessing:** Handling missing values, one-hot encoding categorical variables, and feature scaling.
* 📊 **Exploratory Data Analysis (EDA):** Histograms, heatmaps, and feature correlation.
* 🤖 **Models Implemented:**

  * Logistic Regression (baseline model)
  * Random Forest Classifier (optimized model with feature importance analysis)
* 📈 **Evaluation Metrics:** Accuracy, classification report, confusion matrix.
* 💾 **Model Persistence:** Trained model and scaler are saved using `joblib`.
* 🧪 **User Prediction:** Upload your own dataset (CSV template provided) to get predictions.

---

 🛠️ Tech Stack

* **Python 3**
* **Libraries:**

  * pandas, numpy
  * matplotlib, seaborn
  * scikit-learn
  * joblib
  * kaggle API (for dataset download)

---

 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/ai-heart-disease-predictor.git
   cd ai-heart-disease-predictor
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook or script in Google Colab / Jupyter Notebook.

4. To predict on your own data:

   * Use the provided `heart_user_template.csv` as a reference.
   * Upload your dataset and run the prediction script.

---

 📊 Results

* Logistic Regression Accuracy: \~XX%
* Random Forest Accuracy: \~YY%
* Random Forest provides better performance and interpretable feature importance.

*(You can add screenshots of confusion matrix and feature importance here for better visualization.)*

---

 📂 Project Structure

```
📦 ai-heart-disease-predictor
 ┣ 📜 heart_rf_model.pkl          # Saved Random Forest model
 ┣ 📜 heart_scaler.pkl            # Saved Scaler
 ┣ 📜 heart_user_template.csv     # Sample input template
 ┣ 📜 heart_disease.ipynb         # Main notebook
 ┣ 📜 README.md                   # Project description
 ┣ 📜 requirements.txt            # Dependencies
```

---

 🤝 Contributing

Pull requests are welcome! If you’d like to add improvements (e.g., more ML models, deployment on Streamlit/Flask), feel free to open an issue or submit a PR.

---

 📜 License

This project is licensed under the MIT License.
