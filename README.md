# Government Confidence Prediction Model  

## 📌 Project Overview  
This project uses data from the **World Happiness Report** to explore and predict **confidence in national government** across countries.  
I apply several machine learning models to evaluate which features best explain government confidence and how accurately we can predict it.  

## ⚙️ Technologies  
- Python  
- pandas  
- scikit-learn  
- matplotlib  
- seaborn  

## 🤖 Models Implemented  
- Linear Regression  
- Random Forest  
- Gradient Boosted Trees  

## 📊 Data  
- **Source:** World Happiness Report dataset  
- **Features include:** economic measures, social support, perceptions of corruption, happiness scores, and more.  
- **Target:** Reported confidence in national government.  

## 🔍 Approach  
1. **Data Preprocessing:** Cleaning, handling missing values, and feature selection.  
2. **Exploratory Data Analysis:** Visualization of correlations and feature importance.  
3. **Modeling:** Training and testing three machine learning models.  
4. **Evaluation:** Comparing performance using metrics such as R², RMSE, and feature importance plots.  

## 🚀 Results  
- Random Forest and Gradient Boosted Trees outperformed Linear Regression.  
- Confidence in government is strongly correlated with **perceptions of corruption** and **social support**.  
- The model highlights the importance of governance-related features in explaining trust.  

## Building and Running a Local Instance

## 🛠️ How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/Government-Confidence-Prediction.git
   cd Government-Confidence-Prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
    ```bash
    jupyter notebook DefineAndSolveMLProblem.ipynb
    ```

## Results
- **Correlation analysis** shows that confidence in government is **negatively associated with corruption perceptions (−0.43)** and positively with **freedom to make life choices (+0.41)** and **generosity (+0.27)**.  
- **Model performance (RMSE, lower is better):**  
  - Linear Regression: **0.140 ± 0.006**  
  - Random Forest: **0.106 ± 0.009**  
  - Gradient Boosted Trees: **0.112 ± 0.006**  
- **Random Forest achieved the best predictive accuracy**.  
- Top predictive features: *Perceptions of corruption*, *Freedom to make life choices*, *Generosity*, *GDP per capita*, *Healthy life expectancy*.  

### 📌 Future Work
1. Incorporate more recent World Happiness Report data.
2. Test additional models (XGBoost, Neural Networks).
3. Build a simple dashboard for interactive predictions.
