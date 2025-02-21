# **Bellabeat Data Analysis Project**

## **Project Overview**
This project analyzes Fitbit fitness tracker data to gain insights into how consumers use smart devices and provides strategic recommendations for Bellabeat’s marketing strategy. The findings aim to help Bellabeat enhance user engagement and product development.

## **Business Objective**
- Understand consumer usage patterns of smart fitness devices.
- Identify activity trends and behavior segmentation.
- Provide actionable recommendations for Bellabeat’s marketing and product strategies.

## **Dataset**
- **Source**: Fitabase Data (4.12.16 - 5.12.16)
- **Files Used**:
  - `dailyActivity_merged.csv`
  - `dailyCalories_merged.csv`
  - `dailyIntensities_merged.csv`
  - `dailySteps_merged.csv`
  - `sleepDay_merged.csv`
  - `weightLogInfo_merged.csv`
- **Data Summary**:
  - 33 unique users, 940 activity records.
  - Contains information on steps, calories burned, sleep patterns, and activity levels.

## **Methodology**
### 1. Data Cleaning & Transformation
- Converted date columns to `datetime` format.
- Merged relevant datasets (Activity & Sleep).
- Segmented users based on activity levels.

### 2. Exploratory Data Analysis (EDA)
- Analyzed daily activity trends.
- Examined relationships between steps, calorie burn, and sleep.
- Identified user activity distribution.

### 3. Visualizations
- Activity level segmentation.
- Correlation analysis between steps and calories burned.
- Proportion of different activity intensities.

### 4. Recommendations
- Personalized user engagement strategies.
- Gamification and community-building initiatives.
- Marketing channel optimizations.

## **Key Findings**
- **Average Daily Steps**: ~7,638 steps (~5.5 km).
- **Calorie Burn**: Average ~2,303 calories/day.
- **User Segmentation**:
  - **Sedentary (<5,000 steps)**: High inactivity.
  - **Low Active (5,000 - 7,499 steps)**: Minimal movement.
  - **Somewhat Active (7,500 - 9,999 steps)**: Moderate activity.
  - **Active (10,000 - 12,499 steps)**: Standard fitness level.
  - **Highly Active (>12,500 steps)**: Intense activity.

## **Technologies Used**
- **Python**: Data processing and analysis (`pandas`, `numpy`)
- **Matplotlib**: Data visualization
- **Jupyter Notebook**: Exploratory analysis
- **Seaborn**: Statistical plots

