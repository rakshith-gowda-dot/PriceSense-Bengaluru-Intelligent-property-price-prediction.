# Bengaluru House Price Prediction

**Bengaluru House Price Prediction** is an end-to-end machine learning project that predicts property prices in Bengaluru based on key real estate features such as **location**, **total square footage**, **number of bathrooms**, and **BHK configuration**.

The project achieved an **R² score of 0.8608** using **Ridge Regression** after performing extensive **feature engineering**, **data cleaning**, and **model tuning**.  

The final solution is deployed as a **Flask-based web application** with an intuitive interface, allowing users to input details dynamically and get **instant, sub-second predictions**. This project demonstrates the full lifecycle of a machine learning solution — from raw data preprocessing to production deployment.
<img width="1910" height="1075" alt="Screenshot 2025-08-12 111028" src="https://github.com/user-attachments/assets/9f139aa5-4f30-4cdb-b870-f2f02c884e05" />
<img width="1881" height="981" alt="Screenshot 2025-08-12 111154" src="https://github.com/user-attachments/assets/1849e01e-2f0c-4f46-a130-9300cbbea470" />
<img width="863" height="497" alt="Screenshot 2025-08-13 002026" src="https://github.com/user-attachments/assets/57314099-0fb0-4eeb-9925-9913997def8b" />
<img width="700" height="546" alt="Screenshot 2025-08-13 002114" src="https://github.com/user-attachments/assets/3cbc01f1-af56-4923-b18d-4c7f0cea8c00" />





---

## Objective

To design and deploy a robust machine learning pipeline that:
- Predicts house prices in Bengaluru accurately.
- Handles categorical and numerical data efficiently.
- Delivers real-time predictions via a user-friendly web interface.
- Is optimized for performance and scalability in production environments.

---

## Tools & Technologies Used

- **Python** – Data preprocessing, model training, and backend development.
- **Pandas & NumPy** – Data cleaning, exploration, and feature manipulation.
- **Scikit-learn** – ML pipeline creation, model building, and evaluation.
- **Ridge Regression** – Chosen model for best bias-variance tradeoff.
- **Flask** – Web application framework for deployment.
- **HTML & CSS** – Front-end design for the prediction page.
- **Pickle** – Model and data serialization for quick loading.
- **GitHub** – Version control and project hosting.

---

## Dataset Summary

The dataset includes:
- **Location** – Locality/area in Bengaluru.
- **Total_sqft** – Property size in square feet.
- **Bath** – Number of bathrooms.
- **BHK** – Bedrooms, halls, and kitchens.
- **Price** – Target variable (in lakhs).

### Data Cleaning & Preprocessing Steps:
- Removed missing and invalid entries.
- Dropped unnecessary columns like unnamed indexes.
- Converted size ranges (e.g., "1000-1200") into numerical averages.
- Standardized numeric features.
- Encoded categorical variables using **OneHotEncoder**.
- Scaled numerical features with **StandardScaler**.

---

## Machine Learning Pipeline

1. **Data Splitting** – Train-test split (80-20 ratio) for unbiased evaluation.
2. **Feature Transformation** – One-hot encoding for locations.
3. **Feature Scaling** – StandardScaler for numerical columns.
4. **Model Training** – Linear Regression, Lasso, and Ridge models tested.
5. **Evaluation** – Ridge Regression selected for its **0.8608 R² score** and stability.
6. **Serialization** – Saved model and location list using Pickle for deployment.

---

## Web Application

The Flask application includes:
- **Dynamic location dropdown** (loaded from serialized data).
- **User inputs** for square footage, BHK, and bathrooms.
- **Instant prediction display** without page reload delays.
- **Clean UI** with HTML/CSS styling for a professional look.

---

## Key Features

| Feature | Description |
|---------|-------------|
| **Full ML Pipeline** | Automated preprocessing, encoding, scaling, and prediction. |
| **High Accuracy** | Achieved 0.8608 R² score through tuning. |
| **Fast Predictions** | Sub-second prediction speed using serialized model. |
| **User-Friendly Interface** | Intuitive web form for easy input. |
| **Production Ready** | Pickle-based deployment for seamless integration. |

---

## What I Learned

- Applying **feature engineering** techniques to improve prediction accuracy.
- Building **Scikit-learn pipelines** for clean and modular ML code.
- Evaluating models (Linear, Lasso, Ridge) to select the best performer.
- Using **Flask** for deploying ML models in production.
- Creating interactive **HTML/CSS** frontends for data-driven applications.
- Ensuring quick response times with **Pickle** serialization.

---

## About Me

I’m passionate about building **data-driven solutions** that combine strong **machine learning foundations** with **real-world usability**. My projects integrate technical accuracy, user experience, and production scalability to deliver impactful applications.

**GitHub**: [github.com/rakshith-gowda-dot](https://github.com/rakshith-gowda-dot)  
**LinkedIn**: [linkedin.com/in/rakshith-n-81b34329a](https://www.linkedin.com/in/rakshith-n-81b34329a/)
