# 🎮 Video Game Sales Prediction

This project aims to predict the global sales of video games based on various features like platform, genre, critic scores, and user reviews. By leveraging machine learning techniques, this project provides insights into what makes a game successful and predicts its potential market performance.

---

## 🚀 Objective

The objective of this project is to build a robust classification model to predict the global sales of a video game, using the `Global_Sales` column as the target variable. 

---

## 📊 Dataset

The dataset, inspired by Gregory Smith's web scrape of VGChartz, is enhanced with additional data from Metacritic. It includes:
- Regional sales data
- Game metadata (platform, genre, ESRB rating)
- Critic and user scores

---

## 🔍 Steps Followed

1. **Data Preparation**
   - Loaded and cleaned the dataset by removing NA values and outliers.
   - Combined and structured data for analysis.

2. **Exploratory Data Analysis**
   - Analyzed trends in video game sales by genre, platform, and region.
   - Visualized relationships using correlation matrices.

3. **Feature Engineering**
   - Applied one-hot encoding and frequency encoding to categorical variables.
   - Used F-scores to identify significant features.

4. **Model Development**
   - Implemented multiple regression models:
     - K Nearest Neighbor Regression
     - Linear Regression
     - Random Forest Regression
     - Gradient Boosting Regression
     - Support Vector Regression
     - Decision Tree Regression

5. **Model Tuning**
   - Enhanced model performance with hyperparameter tuning.
   - Experimented with stacking models for improved accuracy.

6. **Conclusion**
   - Summarized the best-performing model and key insights.

---

## 📦 Technologies Used

- **Programming Languages**: Python
- **Libraries**: 
  - Data manipulation: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`, `RandomForestRegressor`, `GradientBoostingRegressor`
- **Tools**: Jupyter Notebook

---

## 🌟 Features

- **Data Cleaning**: Removed noise and inconsistencies in the data.
- **Comprehensive Analysis**: Visualized trends and relationships among features.
- **Robust Models**: Tested multiple regression algorithms for accuracy.
- **Scalable Workflow**: Designed a modular workflow for adaptability and future enhancements.

---

## 📈 Results

- Highlighted the most significant features influencing global video game sales.
- Achieved predictive accuracy through fine-tuned regression models.
- Identified actionable insights into the gaming market.

---

## 🤝 Collaborate

If you're interested in collaborating or have ideas to enhance this project:
1. Fork the repository.
2. Clone it to your local machine.
3. Create a new branch for your contributions.
4. Open a pull request to submit changes.

---

## 📜 License

This project is open-source and available under the MIT License.

---
