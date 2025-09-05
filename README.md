# 🤖 AI-Powered Demand Forecasting for Products

Welcome to the repository for **AI-Powered Demand Forecasting for Products**!  
This project leverages machine learning to predict product demand using multidimensional business and sales data.

---

## 📜 Project Overview

This project was submitted in partial fulfillment of the Minor in AI program by the **Indian Institute of Technology, Ropar**.
![Image Alt](https://github.com/Adityabaan/AI-Powered-Demand-Forecasting-for-Products/blob/54a238ba3fafcdabe6a209dfe8594a7f7c88dda6/iitr-banner.png)
![Image Alt](https://github.com/Adityabaan/AI-Powered-Demand-Forecasting-for-Products/blob/54a238ba3fafcdabe6a209dfe8594a7f7c88dda6/images3.jpeg)

**Goal:**  
Enable businesses to make smarter inventory and marketing decisions by accurately forecasting product demand. The system uses historical sales data, marketing info, pricing, promotions, and seasonality to train AI models that can predict future demand at the product level.

---

## 🚀 Features

- Multi-feature demand forecasting (sales, marketing, pricing, seasonal data, holidays, competitors, and more)
- Multiple machine learning regressors (Random Forest, Gradient Boosting, XGBoost)
- Feature engineering: lag features, seasonality, encoded categories
- Model performance comparison (RMSE, MAE)
- Feature importance and explainability (SHAP)
- Visualizations for top products and seasonal trends
- Easily extendable for new datasets and use cases

---

## 🧑‍💻 Tech Stack

- **Language:** Python 3.x
- **Platform:** Google Colab / Jupyter Notebook
- **Libraries:** pandas, numpy, scikit-learn, xgboost, shap, matplotlib, seaborn

---

## 📊 Dataset

- Historical weekly sales data across multiple years
- Key columns: `Date`, `Product_ID`, `Base_Sales`, `Marketing_Campaign`, `Price`, `Discount`, `Competitor_Price`, `Stock_Availability`, `Seasonal_Trend`, `Public_Holiday`, and `Demand`
- [You can find similar datasets on Kaggle or use your proprietary data]

---

## 🏗️ Project Structure

- **data/** – Raw and processed data files (not included here)
- **notebooks/** – Jupyter/Colab notebooks with full pipeline
- **src/** – Reusable modules (if any)
- **README.md** – This file

---

## ⚡ Quick Start

1. **Clone this repo:**
https://github.com/Adityabaan/AI-Powered-Demand-Forecasting-for-Products.git
2. **Open `notebooks/AI_Demand_Forecasting.ipynb` in Google Colab**
3. **Upload your dataset or use provided sample**
4. **Run each code cell sequentially** to train models and view results
5. **Review model metrics, feature importances, and demand prediction visualizations**

---

## 🗂️ Results & Observations

- **Best Model:** Gradient Boosting with lowest RMSE & MAE
- **Top features:** Lag sales, quarter/seasonality, marketing effect, price
- **Outcome:** AI models closely track real demand trends, enabling effective business planning

---

## 🌟 What Makes This Project Unique?

- Integrates diverse business, price, marketing, and temporal factors for robust demand forecasting
- Provides interpretable insights (not a “black box”)
- Easily adaptable to new industries, products, and real company data
- Developed as part of IIT Ropar's Minor in AI, ensuring academic rigor

---

## 📈 Future Extensions

- Real-time data feeds (social media, weather, economic indicators)
- Deep learning (LSTM-based sequence models)
- Interactive web dashboard for business users

---

## 🧑‍🎓 Acknowledgments

Project by [Your Name].  
Partially fulfilling requirements of the Minor in AI, Indian Institute of Technology, Ropar.

---

## License 📝

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📬 Connect & Feedback

Questions, collaboration ideas, or feedback are always welcome!  
- 📧 Email: [adityabaantripathy@gmail.com](mailto:adityabaantripathy@gmail.com)  
- 🌐 LinkedIn: [Adityabaan Tripathy](https://www.linkedin.com/in/adityabaan-tripathy-6b245323b/)  
- 🐙 GitHub: [Adityabaan Tripathy](https://github.com/Adityabaan)

---

⭐️ If you found this project useful, please star this repo!
