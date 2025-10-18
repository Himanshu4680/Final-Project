# Final-Project
# Empirical Evaluation of the Effect of Design Patterns on Maintainability in Java Software

### 📘 Overview
This project empirically examines how the use of **design patterns** influences **software maintainability** in Java programs.  
Using data from 30 open-source Java projects (>5k LOC each), we compared **pattern classes** and **non-pattern classes** across key maintainability metrics.

### 🧩 Variables
- **Independent Variable:** Use of Design Patterns  
- **Dependent Variable:** Maintainability  
- **Quality Attribute:** Maintainability (measured using MI, CC, CBO, and LCOM)

### 🧠 Methodology
1. **Design Pattern Detection Tool** was used to identify GoF patterns (e.g., Singleton, Factory, Observer).  
2. Classes were labeled as **Pattern** or **Non-Pattern**.  
3. **SonarQube** was used to extract:
   - Maintainability Index (MI)  
   - Cyclomatic Complexity (CC)  
   - Coupling Between Objects (CBO)  
   - Lack of Cohesion of Methods (LCOM)
4. Results were visualized using bar and scatter plots.

### 📊 Key Findings
| Metric | Pattern Classes | Non-Pattern Classes | Observation |
|---------|-----------------|---------------------|--------------|
| **MI** | 78 | 65 | Higher maintainability |
| **CC** | 5 | 8 | Lower complexity |
| **CBO** | 2 | 4 | Lower coupling |
| **LCOM** | 0.2 | 0.45 | Higher cohesion |

**Conclusion:**  
Design patterns improve maintainability by reducing complexity, coupling, and cohesion issues. Singleton and Factory patterns showed the strongest positive effect.

### 🧰 Tools Used
- **SonarQube** – Metric extraction  
- **Python (Matplotlib, Pandas)** – Data analysis & visualization  
- **Design Pattern Detection Tool** – Pattern identification  
- **GitHub** – Project hosting and version control  

### 📁 Repository Contents
- `Final_Course_Project_Report.pdf` – Full report  
- `Dataset.csv` – Summary of all analyzed Java projects  
- `Metrics.csv` – Raw metric values (MI, CC, CBO, LCOM)  
- `MI_bar_chart.png` – Maintainability Index comparison  
- `CBO_LCOM_scatter.png` – Coupling vs Cohesion visualization  

### 👥 Authors
- Kaushalkumar Sharma  
- Sreeja K Shetty  
- Chrystina Joy
- Himanshu Reddy 
