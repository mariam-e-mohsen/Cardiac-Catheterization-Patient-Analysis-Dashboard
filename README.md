# Cardiac-Catheterization-Patient-Analysis-Dashboard
A Power BI dashboard built on real clinical data from  Duke University Medical Center, analyzing 3,504 patients who presented with chest pain symptoms and underwent diagnostic cardiac catheterization. The goal is to uncover patterns that help identify patients with significant coronary artery disease (CAD) based on key clinical variables.

***

## 📊 Dataset

**Source:** [Vanderbilt Biostatistics Repository](https://hbiostat.org/data/repo/acath)  
**Institution:** Duke University — Department of Cardiology  
**Patients:** 3,504  
**Format:** Excel (.xls) — free to use with source attribution

## 🔍 Key Insights

- **34%** of patients were diagnosed with significant coronary artery disease (sigdz = 1)
- **34%** of patients had severe three-vessel or left main disease (tvdlm = 1)
- CAD symptom duration alone is **not a strong predictor** of disease severity — patients without significant disease showed similar symptom durations to those with disease
- Cross-filtering between visuals reveals the distribution pattern across age groups and cholesterol levels

- ## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Microsoft Excel** | Data loading and initial exploration |
| **Power Query (Power BI)** | Data transformation — e.g., converting `cad.dur` from days to months (`/ 30.44`), creating age groups, labeling binary columns |
| **Power BI Desktop** | Dashboard design and interactive visualizations |
| **DAX** | Calculated measures and KPIs |

## 📌 Use Cases

- Practice Healthcare Data Analysis with real clinical data
- Build and showcase Power BI skills in a medical context
- Explore cross-filtering, DAX measures, and data storytelling
- Portfolio project for Healthcare Data Analyst roles

***

## 📜 Data Attribution

> Data obtained from [hbiostat.org/data](https://hbiostat.org/data) courtesy of the **Vanderbilt University Department of Biostatistics**.  
> Original study: Duke University Cardiovascular Disease Databank.

## 👩‍💻 Author

**Mariam E. Mohsen**  
Clinical Pharmacist | Therapeutic Nutrition Diploma  
Aspiring Healthcare Data Analyst  
[LinkedIn]([https://www.linkedin.com/in/](https://www.linkedin.com/in/mariam-e-mohsen/))
