# 📊 AI Assistant Usage in Student Life – Power BI Dashboard

This repository contains a Power BI dashboard that visualizes how students are using AI assistants in their academic and personal lives. The goal of this project is to provide insights into patterns, benefits, and challenges of AI adoption among students.

---

## 🔎 Key Features
- **Interactive Dashboard** – Explore data with slicers for:
  - Student Level
  - Discipline
  - Task Type
- **Usage Analysis** – Track how frequently and for how long students use AI assistants.
- **Session Insights** – Average session length displayed in real-time minutes.
- **Comparative Charts** – Line charts, stacked bar charts, and clustered bar charts for detailed analysis.
- **KPI Metrics** – Highlight important measures such as productivity, adoption rate, and engagement.

---

## 🎯 Purpose
The dashboard helps **educators, institutions, and researchers** understand the role of AI assistants in modern student life, enabling data-driven decision-making for digital learning strategies.

---
## 📂 Dataset Description  

The dataset **`ai_assistant_usage_student_life.csv`** contains student-level AI assistant usage logs.  

### 🔑 Key Columns  
- **Student_Level** → High School, Undergraduate, Graduate  
- **Discipline** → e.g., Biology, Computer Science, Literature  
- **Task_Type** → Writing, Research, Coding, Studying  
- **Sessions** → Number of AI interactions  
- **Session_Length** → Duration in minutes  
- **Satisfaction_Rating** → Rating (1–5 scale)  
- **Outcome** → Assignment Completed, Idea Drafted, Confused, Gave Up  
- **Reuse** → Whether session was reused (`Yes`/`No`)  


## 📊 Dashboards Explained

## 📊 Dashboard 1: Usage Overview  

This dashboard provides a **general overview of AI usage by students**.  

### 🔑 KPI Cards  
- **Total Sessions:** `10K`  
- **Average Session Length:** `20 minutes`  
- **Interactions per Session:** `6`  
- **Reuse Rate:** `70.64%`  

### 📊 Visuals  
- **Sessions Over Time (Line Chart):** Monthly usage trend (Jan–Dec) with peak activity in July & September.  
- **Session Length by Discipline (Bar Chart):** Biology students record the longest sessions (~111 minutes).  
- **Task Type vs. AI Assistance Level (Stacked Bar):** Writing shows the highest reliance on AI.  
- **Sessions by Student Level (Pie Chart):** Distribution: Undergraduate (~59.8%), High School (~20.3%), Graduate (~20%).  

### 🎛️ Slicers  
- Filters: **Student Level, Discipline, Task Type**

  ---

## 📊 Dashboard 2: Outcome & Satisfaction  

This dashboard highlights **student satisfaction and outcomes of AI-assisted sessions**.  

### 🔑 KPI Cards  
- **Average Satisfaction Rating:** `3.42`  
- **Sessions Reused:** `7064`  
- **Sessions Not Reused:** `2936`  

### 📊 Visuals  
- **Satisfaction by Task Type for Student Level (Bar Chart):** Ratings are consistent across tasks (3.3–3.5).  
- **Final Outcome Distribution (Pie Chart):**  
  - Assignment Completed: `47.68%`  
  - Idea Drafted: `28.66%`  
  - Confused: `16.13%`  
  - Gave Up: `7.53%`  
- **Reuse Rate by Discipline & Level (Stacked Bar):** Biology and Computer Science show the highest reuse counts.  
- **Metrics Table (Matrix):** Detailed breakdown of discipline × student level session reuse.  

### 🎛️ Slicers  
- Filters: **Student Level, Discipline, Task Type**  

---

## 🚀 How to Use  

1. Open the **`.pbix` file** in Power BI Desktop.  
2. Connect it with the dataset `ai_assistant_usage_student_life.csv` if needed.  
3. Use slicers to filter data by **Student Level, Discipline, and Task Type**.  
4. Navigate between dashboards:  
   - **Usage Overview** → Usage trends & behavior.  
   - **Outcome & Satisfaction** → Outcomes & student feedback.  

---

## 📌 Key Insights  

- Undergraduates form the majority of AI assistant users.  
- Writing tasks rely most heavily on AI.  
- Average satisfaction is moderate (`3.42/5`).  
- Almost half of sessions result in **Assignment Completion**.  
- Biology and Computer Science show the **highest reuse rates**.  

---

## 🛠️ Tools Used  
- **Power BI** – Dashboard creation  
- **CSV Dataset** – AI assistant usage data  
- **GitHub** – Project versioning & sharing   










