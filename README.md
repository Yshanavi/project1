# Flat Tire Rear - Predictive Maintenance Project

## Overview
This project is part of Volkswagen's Predictive Maintenance initiative aimed at improving the efficiency of test equipment in active safety scenarios. The focus here is on tracking and predicting tire wear, specifically for flat tires on the rear of self-driving platforms.

## Objectives
- Identify features that enable tracking of tire wear, particularly flat tires.
- Analyze relevant sensor characteristics and explore potential feature combinations.
- Propose new features or models for predictive maintenance.
- Determine the need for additional sensors or changes in the checkup process.

## Dataset
- **Total Drives:** 40
  - 10 with tires in good condition.
  - 10 with a slight flat tire on the rear left.
  - 10 with a slight flat tire on the rear right.
  - 10 with a severe flat tire on the rear left and a slight flat tire on the rear right.
- **Data Format:** `.parquet`
- **Preprocessing Notes:**
  - Some unnecessary columns (e.g., file headers and absolute GPS positions) have been removed.
  - Further cleaning may be required based on analysis needs.

## Tasks
1. **Feature Engineering:**
   - Identify sensor signals that indicate tire wear.
   - Develop features based on available sensor data.
2. **Analysis:**
   - Compare datasets from different conditions (good tires vs. flat tires).
   - Use statistical and machine-learning approaches to classify and predict tire wear.
3. **Recommendations:**
   - Suggest changes in checkup procedures or additional sensors for better tracking.
   - Provide actionable insights for implementing predictive maintenance.

## Target Variable
The target column for analysis is identified as **`UFO_test_combined`**, which tracks key performance metrics.

## Deliverables
- A detailed analysis report comparing datasets under different conditions.
- Visualizations and insights from sensor data.
- Feature extraction methods and their predictive power.
- Recommendations for enhanced tire tracking and maintenance strategies.

## Tools and Techniques
- Data processing and visualization libraries: Pandas, NumPy, Matplotlib, Seaborn.
- Machine learning frameworks: Scikit-learn, TensorFlow, or PyTorch.
- Feature engineering and statistical analysis.

## References
1. [UFOpro Overview](https://www.humaneticsgroup.com/products/active-safety-test-equipment/ufopro-ultra-flat-overrunable-robot-platform/ufopro-standard)
2. [Predictive Maintenance in Automotive](https://doi.org/10.3390/mca27010002)

