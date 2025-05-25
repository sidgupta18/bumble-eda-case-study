# Bumble EDA Case Study 🐝

This project is part of my capstone submission for the **NextLeap Data Analyst Fellowship**. It presents a full exploratory data analysis (EDA) of user data from the dating app **Bumble**, with the aim of extracting product-level insights and user behavior patterns that could drive better decisions in matchmaking, targeting, and feature optimization.

---

## 📌 Objective

To uncover demographic, preference, and behavioral insights from Bumble user profiles using Python, and provide data-backed recommendations that could support both **product** and **marketing** strategies.

---

## 🧰 Tools & Libraries Used

- **Python** (Jupyter Notebook)
- **pandas** for data manipulation  
- **numpy** for numerical ops  
- **seaborn** & **matplotlib** for visualization  
- **missingno** for null value inspection  
- **scipy.stats** for correlation analysis  

---

## 🔍 Key Components

### 1. Data Cleaning
- Handled missing values
- Converted data types
- Removed/handled outliers
- Visualized missingness (using `missingno`)

### 2. Data Processing
- Feature binning (e.g., age groups)
- Derived new columns (e.g., pet-friendly score)
- Converted units for clarity

### 3. Data Analysis
- Demographics (age, gender, education)
- Lifestyle & preferences (smoking, drinking, pets)
- Location-based behavior
- Income, height, signs & compatibility patterns

### 4. Visualizations
- Comparative bar plots
- Correlation heatmaps
- Category distribution plots
- Multi-variable insights (e.g., pets vs sign vs age)

---

## 📈 Sample Insights

- **Women with pets** were more likely to specify detailed profile preferences than men.
- **Income distribution** skewed higher in Tier-1 cities, especially among male profiles.
- **Sign-based compatibility** showed weak correlation, debunking app pseudoscience.
- Profiles without height or income data had lower engagement likelihoods.

---

## 🎯 Recommendations

- Add nudges for users with incomplete profiles (e.g., income, pet preferences)
- Tailor marketing campaigns around pet ownership and city-specific lifestyle cues
- Consider removing or reworking zodiac-based filters — low correlation with engagement
- Introduce "profile richness" score as a gamified feature to boost data completeness

---

## 🧠 What I Learned

- Cleaning and understanding real-world data is more time-consuming than model building.
- Visual storytelling is crucial in delivering actionable insights.
- Feature engineering can massively improve how we look at behavioral data.

---

## 🚀 About Me

I'm a data analyst-in-training with a background in **behavioral economics** and **product thinking**. My passion lies in using data to understand people, build cool things, and solve real problems.

> ⚡️ Fun fact: This project was done while balancing cricket, gym, and two dogs 🐶🐕

---

## 📎 Project Files

- `bumble_eda_case_study.ipynb` – Main notebook
- `bumble_user_data.csv` – Primary dataset
- `images/` – Visuals used in the notebook (optional)

---

## 📬 Contact

If you liked this project or want to collaborate, feel free to reach out:
- **LinkedIn**: [Siddhant Gupta](https://www.linkedin.com/in/siddhant-gupta-1273871a3/)
- **Email**: siddhant.gupta18@gmail.com
