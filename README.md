
# 📊 Los Angeles Crime Data Analysis (2020–Present)

This project explores crime data from the **Los Angeles Police Department (LAPD)**, spanning from 2020 to the present. It involves cleaning, processing, analyzing, and visualizing crime patterns to uncover trends, hotspots, and insights on public safety.

---

## 📁 Dataset

**Source**: [Data.gov - LAPD Crime Data](https://data.gov)  
**File Used**: `Crime_Data_from_2020_to_Present.csv`

---

## 🔧 Features of the Analysis

### 🧹 Data Cleaning and Preparation
- Removed irrelevant columns (`weapon desc`, `vict descent`, etc.)
- Converted date columns (`date rptd`, `date occ`) to proper datetime formats
- Converted `time occ` to `HH:MM` format
- Added new features like:
  - `year`, `month`, `weekday`, `month_year`
  - `weekday_type` (Weekday/Weekend)
  - `part 1-2` (Violent vs. Non-violent crimes)

---

## 📈 Exploratory Data Analysis (EDA)

- **Monthly/Yearly Trends**:
  - Tracked total crimes over time
  - Top 5 months with highest and lowest crime rates

- **Crime Type Patterns**:
  - Comparison of violent vs. non-violent crimes
  - Day-of-week and time-of-day analysis

- **Area-wise Crime Distribution**:
  - Identified areas with consistently high crime rates (hotspots)

- **Hotspot Detection**:
  - Used average monthly crime counts to flag high-crime areas

- **Time of Day Patterns**:
  - Analyzed when specific crimes (e.g., burglary, assault) tend to occur

- **Year-over-Year Growth**:
  - Identified crime types increasing over time

---

## 📊 Key Insights

- Certain areas consistently report higher average monthly crimes (possible hotspots).
- Weekends tend to see more violent crimes than weekdays.
- Assaults and burglaries occur frequently during certain time windows.
- Year-over-year trends show some crime types are on the rise.

---

## 📦 Tools & Libraries Used

- **Python**
- **Pandas**
- **Matplotlib / Seaborn**
- **Jupyter Notebook**







