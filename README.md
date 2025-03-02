# Exploring the Impact of Mental Health and Sleep Disorders on Diabetes

## Project Overview  
This project analyzes NHANES 2017-2020 data to explore the relationship between mental health conditions, sleep disorders, and diabetes. The study investigates whether factors like depression, sleep disturbances, and irregular sleep patterns influence HbA1c levels, a key indicator of diabetes risk.  

# Data Analysis
- Merged four NHANES datasets (9,000–15,000 observations each) using an inner join, resulting in a final cleaned dataset of 3,574 observations.
- Preprocessed data using NumPy and Pandas, handling missing values and structuring variables for analysis.
- Conducted statistical analysis using SciPy and Statsmodels, assessing the impact of depression and sleep disturbances on HbA1c levels.
- Built a linear regression model (R2 = 0.845), highlighting the strong influence of sleep patterns on diabetes risk.
- Identified significant effects of depressive symptoms (F=4.37, p<0.05) and sleep disturbances (F=4.18, p<0.05) on HbA1c.
- Visualized key trends using Matplotlib, emphasizing the role of mental health and sleep hygiene in diabetes prevention.

# Tools used
- Programming language: Python
- Libraries: NumPy, Pandas, SciPy, Statsmodels, Matplotlib 

## Repository Structure
- **`Diabetes_MentalHealth_sleep_NHANES.ipynb`** – Jupyter Notebook for data preprocessing, statistical analysis, and visualization
- **`Diabetes_MentalHealth_Sleep_NHANES.pptx`** – Presentation summarizing key findings
- **`Table 1.csv`**, **`Table 2.csv`**, **`Table 3.xlsx`**, **`Table 4.xlsx`** – Raw datasets  
- **`README.md`** – Project documentation

## How to Run the Project
- Clone the repository
   ```bash
   git clone https://github.com/yourusername/Diabetes_MentalHealth_Sleep_NHANES.git
   cd Diabetes_MentalHealth_Sleep_NHANES
-  Install required libraries
   ```bash
   pip install numpy pandas scipy statsmodels matplotlib
- Update file paths if necessary in jupyter notebook
- Run the jupyter notebook to execute analysis
  ```bash
  jupyter notebook Diabetes_MentalHealth_sleep_NHANES.ipynb
- Review `Diabetes_MentalHealth_Sleep_NHANES.pptx` for a summarized presentation of insights.

## Author information
Janaki Ramya Namburu\
email: janakiramyan@gmail.com\
LinkedIn: www.linkedin.com/in/janakiramya
