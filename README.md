

# 📊 **Cause of Death Analysis (EDA)**

Exploratory Data Analysis on global causes of death across countries and years.

## 📁 **Project Overview**

This project performs an exploratory analysis of a dataset containing **global causes of death** across multiple years and countries.
The goal is to understand key mortality drivers, identify regional patterns, compare disease burdens, and answer specific analytical questions using **Python & pandas**.

---

## 🔧 **Tools & Libraries Used**

* **Python**
* **pandas** – data manipulation


---

## 📥 **Dataset**

The dataset is loaded from:

```
cause_of_deaths.csv
```

It includes columns such as:

* `Country/Territory`
* `Year`
* `Malaria`
* `Road Injuries`
* `HIV/AIDS`
* `Lower Respiratory Infections`
* `Conflict and Terrorism`
* ... and several other disease-specific death counts.

---

## 🧹 **Data Cleaning**

Minimal cleaning was required:

* Duplicates were checked and removed.
* `pd.set_option('display.max.columns', 35)` used to view all columns.
* A copy `df2` was created for analysis to preserve original data integrity.

---

## 🔍 **Exploratory Analysis**

The notebook answers multiple real-world analytical questions, including:

### **1. What disease kills Nigerians the most?**

Grouped deaths by year and examined major contributors such as:

* Malaria
* Road Injuries
* Stroke
* Lower Respiratory Infections

---

### **2. What kills Ghanaians the most?**

Similar grouping and comparison for Ghana.

---

### **3. What kills Americans the most?**

Analysis of U.S.–specific mortality drivers.

---

### **4. What country has the highest malaria deaths?**

Grouped by country → summed malaria deaths → ranked.

---

### **5. What country has the lowest malaria deaths?**

Useful for identifying regions with minimal malaria exposure.

---

### **6. Who dies more of HIV/AIDS — men or women?**

Death counts were compared between sexes.

---

### **7. What disease kills Brazilians the most?**

Country-specific trends for Brazil.

---

### **8. Year with the highest malaria deaths**

Total deaths grouped by year.

---

### **9. Country that suffers most from HIV/AIDS**

Ranking based on total HIV/AIDS deaths.

---

### **10. Top 10 countries with the lowest malaria deaths**

---

### **11. Do Nigerians die more from Road Injuries or Malaria?**

---

### **12. How many people have died from Stroke in the U.K (1984–2019)?**

---

### **13. Total deaths from Lower Respiratory Infection in China**

---

### **14. Are Lower Respiratory Infections common in Australia?**

---

### **15. Do Russians die a lot from conflicts?**

---

### **16. Which country is the safest to live in (based on conflict-related deaths)?**

---

### **17. Road Injuries vs Malaria in the U.S.**

---

### **18. Road Injuries vs Malaria in Nigeria**

---

Each question is answered through pandas filtering, grouping, and aggregation operations.




