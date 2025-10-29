# Practical 02 – Introduction to R, RStudio, Git, and Slack  
**Course:** 7COM1079 – Team Research and Development  

---

## 👤 Author Information
**Name:** Sarujan Puvirajan  
**Student ID:** 24156736  
**Mobile:** +44 7466 289817  
**Email:** [saru.contacts@gmail.com](mailto:saru.contacts@gmail.com)  

---

## 🧠 Overview
In this practical, you will:
- Explore the **biopics** dataset (from FiveThirtyEight).  
- Learn R commands for importing, viewing, and summarising data.  
- Work with nominal and numerical variables using `table()`, `unique()`, and `prop.table()`.  
- Import, clean, and analyse real survey data from **7COM1079_survey.xlsx**.  

---

## 📂 1. Biopics Dataset

### 1.1 Importing the Dataset
```r
library(readr)
biopics <- read_csv("biopics/biopics.csv")
print(colnames(biopics))
print(head(biopics))
