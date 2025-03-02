# 🚗 **Car Data Analysis with Python**  
**Uncovering Pricing & Performance Trends in the Automotive Market**  

## 📝 **Project Overview**  
How do *engine specifications, vehicle size, and market category* influence car pricing? This project explores a *real-world car dataset* to uncover insights into *MSRP (Manufacturer’s Suggested Retail Price), fuel efficiency, and popularity trends*.  

Using **Python (Pandas, NumPy, Matplotlib, Seaborn)**, I conducted **exploratory data analysis (EDA)** and **correlation analysis** to detect patterns in vehicle pricing and performance.  

📂 **Dataset Source:** [Car Dataset](https://drive.google.com/file/d/19V7VjHs4J8idTko7NQUT95ZJO2ZQSGWh/view)  
📊 **Google Colab Notebook:** [View Analysis](https://colab.research.google.com/drive/1vU_huGsOO57gFwuNoNDUcN21FLBktviF?usp=sharing)  

---

## 📌 **Data Cleaning & Preprocessing**  
Before analysis, the dataset was cleaned and transformed to ensure accuracy:  
✔️ **Handled Missing Data** – Imputed missing values for key numerical features.  
✔️ **Removed Duplicates** – Ensured unique entries for each car model.  
✔️ **Feature Engineering** – Created new insights, such as *engine performance categories*.  

---

## 📈 **Key Findings & Insights**  

### 🔹 **1. Vehicle Pricing & Market Trends**  
📌 MSRP **varies widely**, with a **mean of $40,615** and **median of $29,985**, indicating a **right-skewed distribution** (influenced by luxury brands).  
📌 **Bugatti** models are extreme outliers, significantly skewing price distributions.  
📌 **Tesla's pricing is high but consistent**, suggesting brand loyalty and perceived value.  
📌 **Larger vehicles (SUVs, luxury cars) have a higher MSRP & greater market popularity**.  

### 🔹 **2. Performance & Pricing Correlation**  
📌 **Higher Engine HP → Higher MSRP** (correlation: **0.65**), except for electric cars.  
📌 Vehicles with **rear-wheel drive** are both the **most expensive and the most popular**.  
📌 Strong correlation (**0.87**) between **Highway MPG & City MPG**, meaning fuel efficiency is stable across different driving conditions.  

### 🔹 **3. Variance & Outlier Analysis**  
📌 **High variance in MSRP for vehicles with 600+ HP**, mainly driven by Bugatti models.  
📌 **10-cylinder engines are the most popular** despite higher costs.  
📌 **All-wheel drive (AWD) vehicles have the highest median price**, while **front-wheel drive (FWD) is the cheapest**.  

---

## 🛠 **Tools & Techniques Used**  
- **Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Techniques Applied:**  
  ✔️ **Data Cleaning & Feature Engineering**  
  ✔️ **Exploratory Data Analysis (EDA)**  
  ✔️ **Correlation Analysis & Statistical Insights**  
  ✔️ **Data Visualization & Trend Analysis**  

---

## 📊 **How to Access & Run This Project**  
1. **Open the Colab Notebook**: [View Analysis](https://colab.research.google.com/drive/1vU_huGsOO57gFwuNoNDUcN21FLBktviF?usp=sharing)  
2. **Download the Dataset**: [Car Dataset](https://drive.google.com/file/d/19V7VjHs4J8idTko7NQUT95ZJO2ZQSGWh/view)  
3. **Run the Python Code** (No additional setup required; runs in Google Colab).  

---

## 📌 **Next Steps & Recommendations**  
🔹 **Further refine pricing models** by incorporating external factors (inflation, consumer demand).  
🔹 **Investigate fuel type impact** on vehicle popularity & MSRP.  
🔹 **Perform time-series analysis** to detect car pricing trends over multiple years.  

---

## 📫 **Explore Further**  
**[LinkedIn](https://www.linkedin.com/in/danhellmuth/)**  
**[GitHub](https://github.com/DanMontHell)**  
**[Tableau](https://public.tableau.com/app/profile/daniel.montreal.hellmuth/vizzes)**  

