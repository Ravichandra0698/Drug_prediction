# 💊 Drug Review Analysis Project

This project analyzes patient reviews on drugs to evaluate their effectiveness, ease of use, satisfaction, and more. It uses regression models, classification algorithms, and visualizations to draw insights and predict drug types and recommendations for medical conditions.

---

## 📁 Dataset

The dataset `Drug.csv` includes anonymized reviews with the following key columns:

- `Drug`: Name of the drug  
- `Condition`: Condition the drug is used for  
- `Reviews`: Number of reviews  
- `Effective`, `EaseOfUse`, `Satisfaction`: Ratings from 1 to 5  
- `Information`: Summary of user feedback  
- `Type`: Drug classification (Generic, Brand)

---

## 📊 Key Features

- **Exploratory Data Analysis**  
  - Histograms, scatter plots, pair plots, and correlation heatmaps  
- **Regression Models**  
  - Linear Regression and OLS Regression  
- **Classification**  
  - Random Forest to predict `Type` based on usage ratings  
- **Drug Recommendation System**  
  - Suggests top-rated drug for each condition  
- **Condition-Based Prediction**  
  - Predicts the drug type and recommendation for a new medical condition input

---

## 🔧 Libraries Used

- `pandas`, `numpy`  
- `matplotlib`, `seaborn`  
- `sklearn`  
- `statsmodels`

---

## 🚀 Running the Project

### 1. Clone the repository:
```bash
git clone https://github.com/<your-username>/drug-review-analysis.git
cd drug-review-analysis
2. Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt
3. Place the dataset:
Ensure Drug.csv is in the root directory.

4. Run the script:
bash
Copy
Edit
python main.py
📌 Example Output
Top drug recommendations for each condition

Regression model output:

Intercept, slope, and MSE

Classification model:

Confusion matrix with accuracy

Prediction:

Given a condition like "Diabetes Type 2", output the predicted drug type and recommendation

🧪 Sample Visualization
📉 Scatter plot of Satisfaction vs. Effectiveness, colored by drug type

🔥 Correlation heatmap with annotated coefficients

🧮 Confusion matrix for model performance

📃 License
This project is licensed under the MIT License.

👤 Author
Ravichandra Lakkappa
GitHub • LinkedIn
