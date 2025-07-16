🌾 Crop Yield Prediction using Machine Learning
📜 Overview
Agriculture is the heartbeat of our Bharat — the soil that sings, the sun that nurtures, the rains that bless. With the rise of Artificial Intelligence, we now blend tradition with innovation. This project, Crop Yield Prediction, is a humble effort to support farmers and agri-planners by using machine learning to predict the crop yield based on various environmental and soil parameters.

It’s not just a project — it’s a promise to the farmers of tomorrow.

🧠 Project Objective
The goal is to predict crop yield (in tonnes/hectare) using features like:

Rainfall (mm)

Temperature (°C)

Humidity (%)

Area (ha)

Soil type / Fertilizer usage (optional)

Crop type / Region (optional)

These predictions can guide decision-making in:

Smart farming

Resource allocation

Risk management

Government policies & planning

🏗️ Project Architecture

+--------------------+
|  CSV Input Dataset |
+--------------------+
           ↓
+------------------------+
|  Data Preprocessing    |
| (nulls, encoding, etc) |
+------------------------+
           ↓
+------------------------+
|    Train/Test Split    |
+------------------------+
           ↓
+----------------------------+
| Machine Learning Model(s) |
| (e.g., Linear Regression, |
|  Random Forest, XGBoost)  |
+----------------------------+
           ↓
+------------------------+
|     Yield Prediction   |
+------------------------+
           ↓
+------------------------+
|   Web App / Streamlit  |
+------------------------+
🛠️ Technologies Used
Python 

Pandas, NumPy for data handling

Scikit-learn for modeling

Matplotlib, Seaborn for visualization

Joblib for model serialization

Streamlit / Flask (optional) for deployment

📊 Dataset
The dataset includes features such as:

Crop type

Region

Average rainfall (in mm)

Temperature range (in °C)

Area under cultivation

Historical yield (label)

You can either use government open-source datasets (e.g., from data.gov.in) or a curated CSV for experimentation.

📈 Model Performance
We experimented with:

Linear Regression – Simple, fast, but limited accuracy

Random Forest – Better performance, handles non-linearity

XGBoost – Best performing in terms of RMSE and R²

You can visualize metrics like:

MAE / RMSE

R² Score

Feature importance

🌱 Future Work
Add weather forecast API integration

Region-wise dynamic recommendations

Soil classification using satellite data

Mobile interface for farmers

Integration with government crop advisory portals

❤️ Acknowledgements
Inspired by the plight of farmers and the power of data

Dataset sources: data.gov.in, Kaggle

Guided by professors and supported by peers

📬 Contact
Ramesh M
B.Tech – Computer Science & Business Systems
📧 ramesh.m.j.2006@gmail.com
