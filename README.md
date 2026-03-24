# 📊 Mutual Fund Overview & Insights

This mutual fund analysis project focuses on identifying top 30 schemes with high return and low risk using Python, Excel, and Power BI.

🛠️ **Tools Used:** Python (Pandas, Scikit-learn), Excel, Power BI  
📁 **Dataset:** More Than 2500 Mutual Fund Schemes (Top 30 Filtered)

---

## 👨‍💻 Project By

**Bakki Tharun Ram Patel**  
B.Tech - Computer Science & Engineering | CMR College of Engineering & Technology, Hyderabad  
📧 tharunpatel9492@gmail.com | 🔗 [LinkedIn](https://www.linkedin.com/in/tharun-patel-a68441355/) | 🐙 [GitHub](https://github.com/Tharunpatel19)

---

## 🧠 Project Goal

To identify **top-performing, low-risk mutual fund schemes** using data-driven techniques and present insights through a dynamic, professional Power BI dashboard.

---

## 🐍 Python-Based Fund Analysis

I started by importing and exploring a dataset of over 2500 mutual fund schemes.  
🔗 [Python Script](https://github.com/Tharunpatel19/mutual-fund-analysis-Dashboard-Python-PowerBI/blob/main/Mutual%20Fund%20Analysis.ipynb)

### 1. Data Cleaning
- Removed unnecessary columns
- Handled missing values
- Standardized numeric formats (returns, expense ratios)

### 2. Data Description & Understanding
- Statistical summaries using Pandas: mean, median, mode, min, max, std deviation
- Analyzed fund distributions across return rates, risk levels, and fund age

### 3. Data Normalization
- Used `MinMaxScaler` from `sklearn.preprocessing` to normalize numeric fields
- Compared returns and expense ratios on a common scale

### 4. Fund Scoring & Ranking
Custom scoring formula based on:
- High 3-Year Returns  
- Low Expense Ratio  
- Moderate Fund Age  
- Consistent 1-Year Return > 0

### 5. Final Output – Top 30 Funds
Extracted the **Top 30 Mutual Funds** with best return-low risk balance  
🔗 [Top 30 Mutual Funds (Excel)](https://github.com/Tharunpatel19/mutual-fund-analysis-Dashboard-Python-PowerBI/blob/main/top_30_mutual_funds.xlsx)

---

## 📈 Power BI Dashboard – Mutual Fund Insights

After processing the data using Python and Excel, I built an **interactive dashboard** in Power BI.   
🔗 [Dashboard Preview Image](https://github.com/Tharunpatel19/mutual-fund-analysis-Dashboard-Python-PowerBI/blob/main/Mutual%20Fund%20Dashboard%20.png)

### 📌 Key Features

#### 📅 Dynamic Filters
- Filter by Fund Type, Category, Sub-category, AMC Name, Risk Level, Fund Rating

#### 📊 Key Visuals & KPIs
- 💼 **Total Investment by Fund Type:** AUM across Equity, Debt, Hybrid, etc.  
- 🔁 **SIP vs Lumpsum Summary Cards:** Monthly SIP trends and minimum lump sum amounts  
- 🧾 **Expense Ratio Comparison:** By Investment Strategy and Sub-Category  
- 📈 **3-Year Returns (Donut Chart):** Category-wise long-term returns  
- 🏆 **Top Performing AMCs:** Average return and AUM  
- 👤 **Fund Manager AUM Comparison:** Largest fund managers by assets  
- 🧠 **Insight Cards:** Auto-generated insights with simple explanations

---

## 🔍 Mutual Fund Investment Insights

| Insight Category | Summary |
|------------------|---------|
| 💼 **Investment Trends** | Equity Funds lead with ₹1.35M Cr total size |
| 👤 **Fund Manager** | Vivek Sharma manages highest AUM: ₹7.3K Cr |
| 📉 **Cost vs Return** | Index Funds have lowest expense ratio: 0.26% |
| 🏦 **Best Return (1Y)** | Bank of India Mutual Fund: 14.4% |
| 🔄 **SIP vs Lumpsum** | Avg. SIP: ₹528.50/month, Lumpsum Min: ₹3.05K |
| ⏳ **3-Year Returns** | Equity Funds: 37.84%, Hybrid: 14.25% |

---

## 🖼️ Dashboard Preview

![Mutual Fund Dashboard Preview](https://github.com/Tharunpatel19/mutual-fund-analysis-Dashboard-Python-PowerBI/blob/main/Mutual%20Fund%20Dashboard%20.png)

---

### 🧠 Final Conclusion

Through this project and dashboard, you can clearly see the **power of investing in mutual funds** when guided by data-driven insights.

By analyzing returns, expense ratios, risk levels, and fund manager performance, I've demonstrated how data analytics can help improve financial decisions.

💡 This dashboard empowers users to make **smarter, low-risk investments** and take control of their financial future. Early and informed mutual fund investment leads to **long-term wealth creation**.

By combining:
- **Python** for filtering and scoring,
- **Excel** for validation and formatting,
- **Power BI** for storytelling and visualization,

I created a tool that helps both beginners and experts make **data-driven, low-risk, high-reward decisions**.

---

## 🔧 Tool Summary

| Tool | Purpose |
|------|---------|
| Python | Data cleaning, scoring, filtering top 30 funds |
| Excel | Formatting, validation, supporting data |
| Power BI | Interactive dashboard and visual storytelling |

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| [Mutual Fund Analysis.ipynb](https://github.com/Tharunpatel19/mutual-fund-analysis-Dashboard-Python-PowerBI/blob/main/Mutual%20Fund%20Analysis.ipynb) | Jupyter Notebook with Python analysis |
| [top_30_mutual_funds.xlsx](https://github.com/Tharunpatel19/mutual-fund-analysis-Dashboard-Python-PowerBI/blob/main/top_30_mutual_funds.xlsx) | Final top 30 filtered mutual funds |
| [Mutual Fund Dashboard.pbix](https://github.com/Tharunpatel19/mutual-fund-analysis-Dashboard-Python-PowerBI/blob/main/Mutual%20Fund%20Dashboard.pbix) | Power BI dashboard file |
| [Mutual Fund Dashboard.png](https://github.com/Tharunpatel19/mutual-fund-analysis-Dashboard-Python-PowerBI/blob/main/Mutual%20Fund%20Dashboard%20.png) | Dashboard image preview |

---

## 🚀 How to Use

1. Clone this repository
2. Run `Mutual Fund Analysis.ipynb` in Jupyter Notebook to see the data processing
3. Open `Mutual Fund Dashboard.pbix` in Power BI Desktop to explore the interactive dashboard

---

✅ **Feel free to fork, explore, and contribute!**

### 🙌 Feedback Welcome

Thank you for exploring my Mutual Fund Analysis project!  
I'm always open to suggestions, improvements, or collaboration ideas.

📩 Connect with me on [LinkedIn](https://www.linkedin.com/in/tharun-patel-a68441355/)  
📧 Or drop an email: **tharunpatel9492@gmail.com**

Your feedback helps me grow and build better data-driven solutions. Let's connect and discuss ideas!
