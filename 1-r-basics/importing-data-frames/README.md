# Importing, Exporting & Data Frame

This project explores a dataset on maternal and paternal characteristics related to birthweight outcomes. It uses **basic R programming** techniques — ideal for early-stage bioinformatics coursework like `SIO3016: Biological Data Analytics`.

---

## 📦 Dataset

**Filename:** `birthweight.csv`  
**Contents:**  
- Maternal and paternal age  
- Smoking status  
- Pre-pregnancy weight  
- Birthweight  
- Geriatric pregnancy indicator  
- Birth date (MM/DD/YYYY)

---

## 🔍 Objectives

- Clean and transform birthweight data using R
- Subset and filter rows with logical indexing
- Apply descriptive statistics
- Convert and manipulate date formats
- Compare mean differences between groups
- Perform a basic chi-squared test

---

## 🧠 Key Analyses

| Analysis | Description |
|---------|-------------|
| 📊 Range of paternal ages | `max - min` of `paternal.age` |
| 🧮 Mean maternal age | Using `mean()` |
| 🚬 Heaviest smoker’s age | `which.max()` on `maternal.cigarettes` |
| ⚖️ Group comparison | Mean `prepregnant.weight` for low vs normal birthweight |
| 🎲 Chi-squared test | Association between geriatric pregnancy and low birthweight |
| 📆 Date parsing | Split `birth.date` into `month`, `day`, `year` |

---

## 📚 Requirements

You’ll need:
- R version ≥ 4.0
- `tidyverse` (optional, for future visualizations)
- `ggplot2` (optional)
- Base R is enough for the current analysis




