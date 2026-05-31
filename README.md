# Tableau Types of Filters Project

## 📌 Project Overview
This project demonstrates the implementation of different types of filters in Tableau. The dashboard enables users to interact with data, perform detailed analysis, and gain insights through various filtering techniques.

## 🎯 Objectives
- Understand Tableau filtering mechanisms.
- Implement different types of filters.
- Improve dashboard interactivity.
- Learn Tableau's Order of Operations.

## 🛠️ Tools Used
- Tableau Desktop
- Microsoft Excel / CSV Dataset

## 📂 Dataset Information
The dataset contains business-related information including:
- Order Date
- Region
- Category
- Sub-Category
- Sales
- Profit
- Segment

---

## 🔍 Types of Filters Implemented

### 1. Extract Filter
**Purpose:** Reduce the amount of data loaded into Tableau.

**Steps:**
1. Connect to the dataset.
2. Click **Extract Data**.
3. Select **Add Filter**.
4. Choose the field and filtering condition.
5. Create the extract.

---

### 2. Data Source Filter
**Purpose:** Restrict data at the data source level.

**Steps:**
1. Open the **Data Source** tab.
2. Click **Add** under Filters.
3. Select the field.
4. Choose filter values.
5. Apply changes.
<img width="1915" height="1024" alt="Screenshot 2026-05-31 203842" src="https://github.com/user-attachments/assets/62e45d62-3f27-4cfd-b47b-6e2af671183b" />
<img width="1919" height="858" alt="Screenshot 2026-05-31 203857" src="https://github.com/user-attachments/assets/76ce2bb2-ae9f-4329-9bff-066e7240f381" />

---

### 3. Context Filter
**Purpose:** Create a primary filter for dependent filters.

**Steps:**
1. Drag a field to the Filters shelf.
2. Right-click the filter.
3. Select **Add to Context**.
4. The filter turns gray, indicating it is now a context filter.
<img width="1919" height="807" alt="Screenshot 2026-05-31 203947" src="https://github.com/user-attachments/assets/d50a307c-6563-4562-bbee-f044091b2681" />

---

### 4. Dimension Filter
**Purpose:** Filter categorical data.

**Steps:**
1. Drag a dimension field (e.g., Region) to the Filters shelf.
2. Select desired categories.
3. Click **OK**.

Example:
- Region = South
- Category = Technology
<img width="1919" height="852" alt="Screenshot 2026-05-31 203913" src="https://github.com/user-attachments/assets/c8dc982e-d404-4dd1-9561-1192372862df" />

---

### 5. Measure Filter
**Purpose:** Filter numerical values.

**Steps:**
1. Drag a measure field (e.g., Sales) to the Filters shelf.
2. Select aggregation (SUM, AVG, etc.).
3. Specify the value range.
4. Click **OK**.

Example:
- Sales > 10,000
<img width="1919" height="924" alt="Screenshot 2026-05-31 203934" src="https://github.com/user-attachments/assets/cc615d58-1b8c-4a44-bcb5-9b396e5c5e8b" />

---

### 6. Date Filter
**Purpose:** Analyze data for specific time periods.

**Steps:**
1. Drag Order Date to the Filters shelf.
2. Select Date Range, Relative Date, or Discrete Date.
3. Configure the desired period.
4. Apply the filter.

Example:
- Orders from 2024 only
<img width="1919" height="914" alt="Screenshot 2026-05-31 204016" src="https://github.com/user-attachments/assets/ce7f3e87-6155-4b8e-a0be-a69d305ff922" />

---

### 7. Top Filter
**Purpose:** Display top-performing records.

**Steps:**
1. Drag a dimension field to Filters.
2. Open the **Top** tab.
3. Select **By Field**.
4. Enter Top N value.
5. Choose the measure.

Example:
- Top 10 products by Sales
<img width="1919" height="1032" alt="Screenshot 2026-05-31 204759" src="https://github.com/user-attachments/assets/c43f2016-132e-4237-b64e-6ab826760892" />

---

### 8. Condition Filter
**Purpose:** Filter based on a custom condition.

**Steps:**
1. Drag a dimension field to Filters.
2. Open the **Condition** tab.
3. Define the condition.
4. Apply the filter.

Example:
- Profit > 5000
<img width="1905" height="950" alt="Screenshot 2026-05-31 205011" src="https://github.com/user-attachments/assets/e99df493-271b-4556-964c-9d9b14988144" />

---

## ⚙️ Tableau Filter Order of Operations

Tableau processes filters in the following order:

1. Extract Filters
2. Data Source Filters
3. Context Filters
4. Dimension Filters
5. Measure Filters
6. Table Calculation Filters

Understanding this order helps create efficient dashboards and avoid unexpected results.

---

## 📊 Dashboard Features
- Interactive filtering
- Dynamic visualizations
- Business performance analysis
- User-friendly design
- Drill-down analysis

---

## 📈 Key Learnings
- Implemented multiple Tableau filter types.
- Learned Tableau Order of Operations.
- Improved dashboard performance using Context Filters.
- Enhanced user interaction with filter controls.
- Applied business intelligence concepts using Tableau.

---

## 🚀 Project Outcome
Developed an interactive Tableau dashboard demonstrating all major filter types. Users can dynamically explore and analyze business data using different filtering techniques.
