# Advertising Impact on Sales 📊

This project analyzes how different advertising channels (**TV, Radio, Newspaper**) impact product sales using **Linear Regression** and presents the results in an interactive **Power BI dashboard**.

---

## 🔍 Project Overview
- Performed **exploratory data analysis (EDA)** to understand the relationship between ad spend and sales.  
- Built a **Linear Regression model** to quantify the effect of each channel.  
- Evaluated model accuracy using **R² Score and RMSE**.  
- Designed a **Power BI dashboard** to visualize insights.  
- Used **OpenAI API** securely (via environment variables) to assist in code explanations & documentation.  


---

## 📂 Repository Contents
- [Advertising Impact on Sales Notebook (Colab)](https://colab.research.google.com/drive/1V9Sci5-h1mJFI3wV6P300UvT9nGUU96S?usp=sharing) → Jupyter/Colab notebook with data analysis and regression model.  
- `Advertising Impact on Sales.pbix` → Power BI dashboard file.  

---

## 📊 Dashboard Preview
![Dashboard Screenshot](Advertising%20Impact%20On%20Sales.png)

### Key Insights
- 📻 **Radio ads** drive the **biggest increase in sales**.  
- 📺 **TV ads** are **highly correlated** with sales but show **smaller incremental impact**.  
- 📰 **Newspaper ads** contribute very little.  
- 📈 The model achieved:  
  - **R² Score: 0.90**  
  - **RMSE: 1.78**  

---

## 💡 Business Impact
This project demonstrates how businesses can **allocate advertising budgets more effectively**:  
- Prioritize **Radio** for maximum incremental sales.  
- Use **TV** for broad visibility but expect smaller incremental returns.  
- Minimize **Newspaper** spend due to low contribution.  

---

## ⚙️ Tech Stack
- **Python** → pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Power BI** → Dashboard & visualization  
- **Google Colab** → Model training & analysis  
- **OpenAI API** → Used for generating insights & explanations (API key handled securely with `os.environ` + `getpass`)  

---

## ▶️ How to Run
1. Open the notebook here → [Google Colab Notebook](https://colab.research.google.com/drive/1V9Sci5-h1mJFI3wV6P300UvT9nGUU96S?usp=sharing)  
2. Run all cells to reproduce results.  
3. Open the Power BI file (`.pbix`) or view the screenshot above for visualization.  

---

## 📝 Project Summary (for GitHub/LinkedIn)
*Built a regression model to analyze the impact of TV, Radio, and Newspaper ads on sales (**R² = 0.90, RMSE = 1.78**) and designed a **Power BI dashboard** to visualize insights. Used OpenAI API for code documentation & insights generation.*
