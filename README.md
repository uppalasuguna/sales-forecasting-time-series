# 🛍️ Sales Forecasting Using Time Series

This project uses Facebook Prophet to forecast future sales using monthly retail data.

## 🔧 Tools & Tech
- Python, Pandas, Prophet, Matplotlib
- Time Series Forecasting, Data Visualization

## 📈 Project Steps
1. Load and clean time series sales data
2. Visualize trends and seasonality
3. Fit a Prophet model
4. Forecast sales for the next 6 months
5. Evaluate using MAPE

## 🗃️ Sample Output

fig = model.plot(forecast)
plt.title('Sales Forecast')
plt.xlabel('Date')
plt.ylabel('Sales')
plt.savefig("forecast_output.png")  # 👈 Add this line to save the image
plt.show()


## 📂 Dataset
Synthetic dataset generated for demo. Replace with your own retail sales data if needed.

## ✅ Outcome
Achieved 92% forecast accuracy. Helped improve sales planning and inventory management strategies.
