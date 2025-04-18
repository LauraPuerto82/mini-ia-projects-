# 🏠 Real Estate Price Prediction with Neural Networks

This project applies a deep learning model to predict housing prices based on various property features.  
The goal is to estimate the sale price of homes in King County, USA, using features like square footage, number of bedrooms, renovations, location, and more.

---

## 📚 Context

This notebook is based on the guided project *"Deep Learning for Real Estate Price Prediction"* from Coursera.  
The original lab has been **carefully reviewed, corrected, and extended** to ensure best practices and to showcase it as part of my AI learning portfolio.

Key improvements made:

- 🔍 Detected and fixed **data leakage** in the original pipeline.
- 🧪 Restructured the preprocessing steps to ensure proper model training.
- 📈 Added new model architectures and optimization strategies.
- 🧼 Cleaned and documented the notebook to be clear, reproducible, and portfolio-ready.

---

## 🎯 Objectives

- Explore and understand the dataset  
- Preprocess the data (select features, scale properly, avoid leakage)  
- Build and train neural networks using Keras  
- Evaluate models using RMSE, MAE, MSE, R², and Adjusted R²  
- Tune the architecture to improve performance  
- Compare results across different feature sets and network depths

---

## 📂 Project Structure

| File | Description |
|------|-------------|
| `Deep Learning for Real Estate Price Prediction.ipynb` | Main notebook with all code, visualizations, and evaluations |
| `data/kc_house_data.csv` | Input dataset used in the project (King County house sales) |
| `README.md` | This file, explaining the context and structure of the project |
| `requirements.txt` | Dependencies to reproduce the environment |

---

## 🧠 Dataset

The dataset contains real estate sales data for King County (Washington, USA), including property attributes such as:

- Living area (`sqft_living`)
- Number of bedrooms and bathrooms
- Year built and renovation year
- Zip code and location
- Lot size and condition

📍 [Kaggle: House Sales in King County](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)

---

## 📊 Model Results (Best Configuration)

| Metric | Value |
|--------|-------|
| RMSE   | ~130,000 USD |
| MAE    | ~73,000 USD |
| R²     | ~0.87 |
| Adjusted R² | ~0.87 |

---

## ⚙️ How to Run This Project

To reproduce this notebook locally, follow these steps:

1. Clone the repository  
2. Navigate to the project folder  
3. (Optional but recommended) Create a virtual environment  
4. Install dependencies:

```bash
pip install -r requirements.txt

5. Run the notebook

```bash
jupyter notebook


Make sure the file kc_house_data.csv is located in the data/ folder.

## 🚀 Notes

- All preprocessing is performed **after splitting the data**, to prevent leakage.
- Both minimal and extended feature sets are explored.
- Multiple neural network architectures were tested and compared.

---

## 👩‍💻 Author

**Laura Puerto**  
Software Developer | AI Learner  
🔗 [My Portfolio](https://laurapuerto82.github.io/laura-puerto-portfolio/index.html)  
🔗 [Main Mini-Project Repository](https://github.com/LauraPuerto82/mini-ia-projects)

