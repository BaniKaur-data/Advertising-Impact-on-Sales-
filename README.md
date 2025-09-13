# Advertising Impact on Sales 📊  

This project analyzes how different advertising channels (**TV, Radio, Newspaper**) impact product sales using **Linear Regression** and presents the results in an interactive **Power BI dashboard**.  

## 🔹 Project Overview  
- Performed **exploratory data analysis (EDA)** to understand the relationship between ad spend and sales.  
- Built a **Linear Regression model** to quantify the effect of each channel.  
- Evaluated model accuracy using **R² Score** and **RMSE**.  
- Designed a **Power BI dashboard** to visualize insights.  
- Used **OpenAI API** securely (via environment variables) to assist in code explanations & documentation.  

## 📂 Repository Contents  
- `Advertising_Impact_on_Sales.ipynb` → Colab notebook with data analysis and regression model.  
- `Advertising Impact On Sales.pbix` → Power BI dashboard file.  
- `Advertising Impact On Sales.png` → Dashboard screenshot.  

## 📊 Dashboard Preview  
<img width="2559" height="1550" alt="Screenshot 2025-09-12 234611" src="https://github.com/user-attachments/assets/bb46b29c-88e5-4eff-b031-3b835ca87778" />

### Key Insights  
- **Radio ads** drive the **biggest increase** in sales.  
- **TV ads** are **highly correlated** with sales but show **smaller incremental impact**.  
- **Newspaper ads** contribute very little.  
- The model achieved:  
  - **R² Score**: **0.90**  
  - **RMSE**: **1.78**  

## ⚙️ Tech Stack  
- **Python** → pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Power BI** → Dashboard & visualization  
- **Google Colab** → Model training & analysis  
- **OpenAI API** → Used for generating insights & explanations (API key handled securely with `os.environ` + `getpass`)  

## ▶️ How to Run  
1. Open the notebook in Colab → [Click here to view in Colab](https://colab.research.google.com/drive/1V9Sci5-h1mJFI3wV6P300UvT9nGUU96S?usp=sharing)  
2. Run all cells to reproduce results.  
3. Open the Power BI file (`.pbix`) or view the screenshot for visualization.  

---

### 🔹 Project Summary  
**“Built a regression model to analyze the impact of TV, Radio, and Newspaper ads on sales (R² = 0.90, RMSE = 1.78) and designed a Power BI dashboard to visualize insights. Used OpenAI API for code documentation & insights generation.”**
