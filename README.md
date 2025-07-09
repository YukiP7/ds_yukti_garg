# 🧠 Sentiment-Driven Trading Behavior Analysis

This project analyzes how **trading behavior (profitability, risk, volume, leverage)** aligns or diverges from **Bitcoin market sentiment (Fear vs Greed)** using real-world data.

---

## 📁 Project Structure

ds_yukti_garg/
- ├── notebook_1.ipynb # Core analysis notebook
- ├── csv_files/
- │ └── merged_data.csv # Combined trade & sentiment data
- ├── outputs/
- │ ├── *.png # Visualizations
- ├── ds_report_trading_strategies.pdf # Final report with insights
- └── README.md # This file


---

## 📊 Objective

- Understand how trader actions vary under **Fear** and **Greed** sentiment.
- Derive actionable insights to enhance trading strategy and risk management.
- Use visual and statistical analysis to uncover hidden behavioral patterns.

---

## 📂 Datasets Used

1. **Bitcoin Market Sentiment Dataset**  
   - Columns: `Date`, `Classification` (Fear, Greed, Neutral)

2. **Hyperliquid Historical Trader Data**  
   - Includes: `Execution Price`, `Size USD`, `Side`, `Start Position`, `Closed PnL`, `Fee`, etc.

3. **Merged Dataset**  
   - Created by aligning trades with daily sentiment via `Date`.

---

## 🔍 Key Insights

- **More trades and higher profitability during Greed** phases.
- **Fear periods show risk aversion** — smaller trade sizes and more short positions.
- **Leverage usage increases with optimism**.
- **Profitability is not strongly correlated with position size**, indicating timing/strategy matters more than size alone.

---

## 📈 Visualizations

- 📊 Daily Trade Counts
- 💰 Average PnL Over Time
- 📉 Start Position & Leverage Analysis
- 📚 Correlation Heatmap
- 🎯 Position Type Distribution by Sentiment

---

## 💡 Trading Strategy Recommendations

- **Scale positions cautiously during Greed**, when market conditions are favorable.
- **Reduce trade frequency or size during Fear**; prioritize high-confidence setups.
- Use sentiment as a **feature in trading algorithms** or as a filter to time entries and exits.
- Avoid over-leverage in Fear zones — fees and volatility can cause losses even in small positions.

> 🔄 Full details in: [`ds_report.pdf`](./ds_report.pdf)

---

## 🚀 How to Run

1. Open `notebook_1.ipynb` in Google Colab or Jupyter
2. Ensure the dataset (`merged_data.csv`) is in `csv_files/`
3. Run all cells to reproduce visuals
4. Outputs will be saved in `/outputs` folder

---

## 📌 Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter / Colab Notebook
- GitHub (for versioning and hosting)

---

## 📬 Contact

For queries, reach out to:  
**Yukti Garg**  
📧 `gargyukti112@gmail.com`  
🌐 [LinkedIn]([https://www.linkedin.com/in/yukti-garg-8397b4218/])

---

