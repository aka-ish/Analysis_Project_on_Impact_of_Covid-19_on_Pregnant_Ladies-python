📊 Impact of Covid-19 on Pregnant Women – Data Analysis Project

📌 Project Overview

This project analyzes a dataset of 10,772 pregnant women to understand the impact of the COVID-19 pandemic on maternal health, mental well-being, and birth outcomes. The focus is on exploring relationships between maternal age, education, household income, depression, anxiety levels, and mental health indicators.

---
<img width="1384" height="541" alt="image" src="https://github.com/user-attachments/assets/0fdfd239-7f94-46fa-b2fe-0d69cc9102fe" />

---

## 📊 Dataset Description

The dataset consists of several variables related to maternal demographics, psychological health, perceived threats during the pandemic, and birth outcomes.

### Maternal and Household Characteristics

* **Maternal_Age**: Maternal age (in years) at intake.
* **Household_Income**: Total household income in 2019, before taxes and deductions.
* **Maternal_Education**: Maternal education level:

  * Less than high school diploma
  * High school diploma
  * College/trade school
  * Undergraduate degree
  * Master's degree
  * Doctoral degree

### Psychological Health

* **EPDS (Edinburgh Postnatal Depression Scale)**: Depression screening tool.

  * 0–9 → Normal, low likelihood of depression
  * 10–12 → Possible depression (borderline)
  * 13 or higher → Likely depression (further evaluation needed)
* **PROMIS_Anxiety**: Anxiety score ranging from 7–35, where higher scores indicate greater severity.

### Birth Outcomes

* **GAbirth**: Gestational age at birth (weeks).
* **Delivery_Date**: Delivery date (converted to month/year).
* **Birth_Length**: Infant length at birth (cm).
* **Birth_Weight**: Infant weight at birth (grams).
* **Delivery_Mode**: Mode of delivery (Vaginal / Caesarean-section).
* **NICU_stay**: Infant admitted to NICU (Yes/No).

### Perceived Threats During COVID-19

* **Threaten_Life**: Perceived danger to mother’s life during COVID-19 (0–100).
* **Threaten_Baby_Danger**: Perceived danger to baby’s life during COVID-19 (0–100).
* **Threaten_Baby_Harm**: Worry about COVID-19 harming unborn baby (0–100).

### Additional

* **Language**: Language in which the survey was completed.

---

## 🛠️ Tools and Libraries

The project uses the following Python libraries:

* **NumPy** → Numerical computations.
* **Pandas** → Data manipulation and cleaning.
* **Matplotlib** → Data visualization (basic plots).
* **Seaborn** → Advanced and aesthetic statistical visualizations.
---

## 📈 Key Analyses

1. **Data Cleaning & Preprocessing**

   * Handling missing values.
   * Converting categorical variables into usable formats.
   * Creating summary statistics.

2. **Descriptive Statistics**

   * Distribution of maternal age, income, and education.
   * Frequency of delivery modes and NICU admissions.

3. **Psychological Health Analysis**

   * EPDS score distributions and depression categorization.
   * Correlation of anxiety levels with maternal income and education.

4. **Perceived Threats Analysis**

   * Distribution of perceived maternal and fetal risks during COVID-19.
   * Associations with mental health outcomes (EPDS, PROMIS_Anxiety).

5. **Maternal Mental Health**
     **EPDS (Depression Scale)**
     * Women aged 25–38 generally had low depression/anxiety levels, indicating a safer reproductive window.
     * Women conceiving after 42 showed significantly higher risk of postnatal depression and anxiety.

 6. ** PROMIS Anxiety**
       * Higher scores correlated with lower household income and increased perception of life threat during the pandemic.

---

## 📊 Example Visualizations

* Histogram of **Maternal Age**.
* Heatmap of correlations between **EPDS, Anxiety, Threat Perceptions, and Birth Outcomes**.
* Boxplots comparing **Anxiety Levels** across education categories.
* Interactive plots of **Birth Outcomes over Time (Delivery_Date)**.

---

## 📝 License

This project is for **research and educational purposes only**. Dataset details should be handled with care, respecting participant confidentiality.
