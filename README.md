# Data Cleaning, Data Curation and Exploratory Data Analysis of Crime in India

# Project Overview:

This project presents an **Exploratory Data Analysis (EDA)** and data curation study of crime data in India, analysed both **state-wise** and **crime-head-wise**.

The analysis uses data from the **National Crime Records Bureau (NCRB)** and considers a five-year period from **2018 to 2022**. The project focuses on understanding patterns in crime rates and comparing the number of cases reported with the number of cases for which charge sheets were filed.

The work was prepared by:

- **Arunodoy Pramanik**
- **Debadrito Saha**

---

# Objectives:

The main objectives of the project were to:

- Explore crime-related data collected from the NCRB.
- Perform data curation and exploratory analysis.
- Study crime rates per lakh population across Indian states.
- Compare **IPC** and **SLL** crime categories.
- Visualize state-wise crime-rate patterns using maps of India.
- Compare the number of cases **reported** with the number of cases **charge-sheeted**.
- Identify patterns and relationships across the period **2018–2022**.

The presentation describes EDA as involving raw data collection, data visualization, data cleaning/transformation, and identification of patterns and relationships.


# Dataset:

**National Crime Records Bureau (NCRB)**

# Time Period: 2018–2022

# Analysis Dimensions:

The project examines the data from two major perspectives:

1. **State-wise analysis**
2. **Crime-head-wise analysis**

For the crime-rate analysis, the project focuses on:

- **2022 – IPC crimes**
- **2022 – SLL crimes**
- **2021 – IPC crimes**
- **2021 – SLL crimes**

Crime rate is represented **per lakh population**.

# Exploratory Data Analysis (EDA):

# 1. State-wise Crime Rate Analysis:

The project visualizes crime rates across the states of India using maps.

The analysis covers:

| Year | Category |
|------|----------|
| 2022 | IPC crimes |
| 2022 | SLL crimes |
| 2021 | IPC crimes |
| 2021 | SLL crimes |

This allows the geographical distribution of crime rates to be explored across different states.

# 2. Reported Cases vs Charge-Sheeted Cases:

The project also compares the number of cases reported with the number of cases for which charge sheets were filed.

A total of **10 crime categories** were selected:

# IPC Crimes:

- Murder
- Rape
- Kidnapping and Abduction
- Extortion and Blackmailing
- Dacoity

# SLL Crimes:

- Dowry Prohibition Act
- Protection of Children from Sexual Offences Act
- Passport Act
- Child Labour Act
- Prohibition Act (State)

# Tools & Technologies:

The analysis was performed using **Python** in Google Colab.

# Python Libraries:

# Pandas:

Used for data analysis, manipulation, cleaning, transformation, and selection of rows and columns.

# NumPy:

Used for numerical computing, array-based operations, and efficient mathematical and logical operations.

# Matplotlib:

Used for creating visualizations such as:

- Line plots
- Bar charts
- Histograms
- Scatter plots
- Pie charts
- Other graphical representations

# Environment:
1. Google Colab
2. Jupyter/Colab Notebook environment
   
# Key Findings:

# IPC Crimes – Charge-Sheet Trends:

According to the analysis presented:

1. **Murder:** The percentage of cases for which a charge sheet was formed varied between approximately **80% and 90%** during 2018–2021.
2. **Rape:** The percentage varied between approximately **70% and 85%** over the five-year period.
3. **Kidnapping and Abduction:** The percentage remained comparatively low, at approximately **35%–37%**.
4. **Extortion and Blackmailing:** The percentage was approximately **65%–73%** during 2018–2021 and was reported at around **39% in 2022**.
5. **Dacoity:** The percentage was approximately **78%–83%** during 2018–2021 and was reported at around **45% in 2022**.

# SLL Crimes – Charge-Sheet Trends:

The presentation reports the following observations:

1. **Dowry Prohibition Act:** Approximately **70%–80%** of cases had charge sheets filed across 2018–2022.
2. **Protection of Children from Sexual Offences Act:** Approximately 80%–90%.
3. **Passport Act:** Approximately **47.5% in 2018**, followed by an improvement to an average of around **85% over the next three years**, before falling to approximately **50% in 2022**.
4. **Child Labour (Prohibition and Regulation) Act:** Approximately **81%–93%**.
5. **Prohibition Act (State):** Approximately **84.6% in 2018**, increasing to around **95%** in subsequent years.

# Overall Trends Reported in the Presentation:

The presentation highlights several broad observations:

1. Charge-sheet percentages for crimes such as **murder, rape, and dacoity** were generally reported in the **75%–90% range during 2018–2021**.
2. **Kidnapping and abduction** showed a substantially lower charge-sheet percentage in the presented analysis.
3. The presentation reports a notable decline in the charge-sheet percentage for the analysed IPC crimes in **2022**.
4. Most of the analysed **SLL crimes** were reported to have charge-sheet percentages between **70% and 90%**, with some exceptions.
5. Several of the analysed SLL categories showed an overall improvement in charge-sheet percentages over the period.

The presentation also mentions the **COVID-19 pandemic and possible limitations in police resources** as one possible explanation for the reported 2022 decline. This is presented in the original work as a possible reason rather than an independently established causal conclusion.

# Visualization:

A major part of the project is the visualization of **crime rates per lakh population across Indian states**.

The analysis uses maps of India to make geographical patterns easier to identify and compare between:

- 2021 vs 2022
- IPC vs SLL crimes

The presentation reports higher crime-rate observations for states including **Kerala, Gujarat, and Haryana** in the analysed 2021–2022 data, while noting comparatively lower values in several north-eastern and eastern states.

# Analytical Flow:

The project follows the general EDA workflow described in the presentation:

Raw Data Collection
        ↓
Data Curation / Cleaning
        ↓
Data Transformation
        ↓
Exploratory Data Analysis
        ↓
Statistical & Visual Analysis
        ↓
Pattern Identification
        ↓
Interpretation of Results

# What This Project Demonstrates:

Through this project, the following data-analysis concepts were explored:

- Exploratory Data Analysis
- Data curation
- Data cleaning and transformation
- Numerical data analysis
- State-wise analysis
- Crime-head-wise analysis
- Comparative analysis
- Data visualization
- Geographical visualization
- Pattern and trend identification
- Interpretation of real-world datasets
Adjust the structure according to the files actually included in the repository.

# Authors:

**Arunodoy Pramanik**  
**Debadrito Saha**

# Data Source:

The project uses crime-related data from the **National Crime Records Bureau (NCRB)** for the period **2018–2022**.

For reproducibility or further analysis, the original NCRB datasets and their corresponding metadata should be included or linked in the repository where permitted.

# Conclusion:

This project demonstrates how **Exploratory Data Analysis can be used to transform a large real-world dataset into interpretable patterns and visual insights**.

By combining state-wise crime-rate visualization with crime-head-wise comparisons of reported and charge-sheeted cases, the project provides an analytical view of crime-related data in India over the 2018–2022 period.

