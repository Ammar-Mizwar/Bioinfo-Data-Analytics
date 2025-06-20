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

## ❓ Your Tasks / Research Questions

Below are a series of questions you'll answer using **basic R programming** skills:

---

### 1. 📊 What is the range of paternal ages?

- Use `max()` and `min()` to find the difference.
- Handle missing values properly.

---

### 2. 🧮 What is the mean maternal age?

- Use `mean()` with proper `na.rm = TRUE` handling.

---

### 3. 🚬 What is the age of the mother who smoked the most?

- Use `which.max()` on `maternal.cigarettes` to find the row.
- Extract the corresponding `maternal.age`.

---

### 4. ⚖️ Is there a difference in **pre-pregnancy weight** between mothers of low vs. normal birthweight babies?

- Filter the data into two groups based on `low.birthweight`.
- Calculate the mean `maternal.prepregnant.weight` for each group.
- Compare and interpret which group had the higher average.

---

### 5. 🎲 Is there a significant association between **geriatric pregnancy** and **low birthweight**?

- Use a chi-squared test to test independence between the two categorical variables:
  - `geriatric.pregnancy`
  - `low.birthweight`

---

### 6. 📆 Can you extract **day, month, and year** from the `birth.date` column?

- Use `strsplit()` and a custom function to split the MM/DD/YYYY format.
- Append new columns: `month`, `day`, and `year`.

---

## 📚 Bonus (Optional)

- What is the **standard deviation** of paternal age?
- Can you convert the `"smoker"` column into a logical `TRUE/FALSE` format?

---

## 💾 Output

All answers are included in:

📄 [`importing-data-frames.Rmd`](./importing-data-frames.Rmd)  
📊 Optional report (knit): `importing-data-frames.html`

---


