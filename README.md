# Create a README.md file content
readme_content = """
# 📘 Cognifyz Technologies – Data Science Internship

**📂 Internship Domain:** Data Science  
**👤 Intern Name:** Mihir Milind Ughade  
**📧 Email:** mihirughade0804@gmail.com  
**🔗 LinkedIn:** [mihir-ughade-00601223a](https://www.linkedin.com/in/mihir-ughade-00601223a)  
**💻 GitHub:** [mihir0804](https://github.com/mihir0804)

---

## 📌 Project Summary

This repository documents the tasks completed during my **Data Science Internship** at **Cognifyz Technologies**. The project involved end-to-end data analysis on a restaurant dataset, covering data cleaning, feature engineering, predictive modeling, and insightful data visualizations using Python.

---

## ✅ Completed Tasks

### 🔹 Level 1 – Data Exploration & Preprocessing
- Handled missing values
- Explored `Aggregate rating` distribution
- Identified class imbalance

### 🔹 Level 2 – Price Range Analysis
- Found the most common price tier
- Compared average ratings by price range
- Created a pie chart showing price range distribution

### 🔹 Level 3 – Predictive Modeling
- Built regression models: Linear, Decision Tree, Random Forest
- Evaluated models with MAE, RMSE, and R² Score
- Visualized important features using bar plots

### 🔹 Level 3 – Data Visualization
- Plotted ratings distribution
- Compared ratings by Cuisine and City
- Visualized Votes vs Rating scatter

---

## 🧰 Tech Stack
- Python (Jupyter Notebook)
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib

---

## 📷 Screenshots & Outputs
<img width="704" height="470" alt="image" src="https://github.com/user-attachments/assets/2689244a-8a80-478f-ba30-6cc561693e3f" />
<img width="704" height="470" alt="image" src="https://github.com/user-attachments/assets/87f703d7-a11c-4199-9023-69f9dae28dc4" />
<img width="704" height="470" alt="image" src="https://github.com/user-attachments/assets/c4f2bb91-531c-4116-8a6d-bebb78b7e05d" />


---

## 📤 LinkedIn Post Template
> ✅ Successfully completed my **Data Science Internship** at **Cognifyz Technologies**.  
> Built regression models to predict restaurant ratings and uncovered data-driven insights using Python.  
> 💡 Tools: Pandas, Scikit-learn, Seaborn  
> 🔗 GitHub: [github.com/mihir0804](https://github.com/mihir0804)  
>  
> #cognifyz #cognifyztech #datascience #machinelearning #internship

---

## 📞 Contact
For queries or collaboration, feel free to reach out via email or LinkedIn.
"""

# Save to a README.md file
readme_path = "/mnt/data/README_Mihir_Ughade_Cognifyz_DS.md"
with open(readme_path, "w", encoding="utf-8") as f:
    f.write(readme_content)

readme_path
