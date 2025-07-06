# GPA & IQ Correlation and Prediction Project

This project analyzes the relationship between students' GPA and IQ, and builds predictive models to estimate IQ based on GPA (and gender). The workflow includes data cleaning, exploratory analysis, correlation calculation, and regression modeling.

## Project Structure

- **gpa_iq.csv**: The dataset containing GPA, IQ, and gender information.
- **gpa_iq_analysis.ipynb**: Jupyter Notebook with all code, analysis, visualizations, and conclusions.

## Main Steps

1. **Data Preparation**
   - Remove duplicates and unnecessary columns.
   - Check for missing values.

2. **Exploratory Data Analysis**
   - Visualize the relationship between GPA and IQ, colored by gender.

3. **Correlation Analysis**
   - Calculate Pearson correlation between GPA and IQ (overall and by gender).

4. **Predictive Modeling**
   - Build a simple linear regression model to predict IQ from GPA.
   - Build a multiple linear regression model to predict IQ from GPA and gender.
   - Evaluate models using R², MSE, and an easy-to-understand “accuracy” metric (percentage of predictions within ±10 IQ points).

5. **Visualization**
   - Scatter plots comparing actual and predicted IQ values for both models.

6. **Conclusions**
   - Discuss findings, limitations, and recommendations.

## Results Summary

- The correlation between GPA and IQ is moderate.
- Including gender as a feature slightly improves prediction accuracy.
- About 70–80% of predictions are within ±10 IQ points of the actual value.
- The dataset is small and limited, so results should not be used for real-world decisions.

## Requirements

Install dependencies with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

## Usage

1. Clone the repository.
2. Open `gpa_iq_analysis.ipynb` in Jupyter Notebook or VS Code.
3. Run all cells to reproduce the analysis and results.

## Disclaimer

This project is for educational purposes only. The dataset is small and limited in scope; do not use these models for real-world decision-making.

---

**Author:** [Your Name]  
**License:** MIT
