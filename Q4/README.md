# Supply Chain Analytics: Correlation Matrix Visualization

**Author:** 24f1001434@ds.study.iitm.ac.in  
**Organization:** OptimalFlow Logistic

---

## 📌 Business Context
OptimalFlow Logistics is a supply chain consulting firm that helps manufacturing companies optimize procurement and inventory management processes.  
They analyze relationships between key supply chain metrics to identify bottlenecks, predict delivery issues, and optimize cost structures.  

A **major automotive manufacturer** engaged OptimalFlow to analyze **supplier performance data** from 77 procurement transactions over the past quarter.  
The goal is to understand how different supply chain variables interact, to improve **supplier selection, inventory planning, and cost optimization**.

---

## 📊 Dataset Variables
The dataset contains the following supply chain metrics:

- **Supplier_Lead_Time** → Days from order placement to delivery  
- **Inventory_Levels** → Current stock quantities (units)  
- **Order_Frequency** → Number of orders placed per month  
- **Delivery_Performance** → On-time delivery rate (%)  
- **Cost_Per_Unit** → Unit cost in dollars ($)  

---

## 🧾 Your Task
We performed **Correlation Analysis** and created a **visual heatmap** using Excel best practices.

### Steps:
1. **Generate Correlation Matrix**
   - Use Excel **Data Analysis ToolPak**  
   - `Data → Data Analysis → Correlation`  

2. **Create Heatmap with Conditional Formatting**
   - Copy correlation matrix into a new sheet  
   - Select correlation values (not labels)  
   - `Home → Conditional Formatting → Color Scales`  
   - Choose **Red (low) → White → Green (high)** palette  

3. **Export Results**
   - Screenshot the heatmap (`400x400` to `512x512` px) → `heatmap.png`  
   - Export correlation values as `correlation.csv`  

---

## 🗂️ Repository Structure
