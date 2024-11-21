# Haberman-Analysis

The Haberman's Survival Dataset contains data from a study conducted on patients who underwent surgery for breast cancer. The dataset focuses on analyzing the survival status of patients over a period of 5 years after surgery. It includes three key features:

1. Age of the patient at the time of surgery.
2. Year of surgery (ranging from 1958 to 1969).
3. Number of positive axillary lymph nodes detected.


    The target variable is the survival status, indicating whether a patient survived 5 years or longer post-surgery. This analysis aims to explore patterns, derive insights, and apply predictive models to classify survival status.











## 📄**Data Quest**
 






The Haberman dataset was explored to understand the features, distribution, and correlations. Key observations include:  

- **Dataset Overview**:  
  - The dataset consists of 305 records with 3 features (Age, Year of Surgery, Number of Nodes) and 1 target variable (Survival Status).  
  - No missing values or null entries were present.  
  - Duplicates exist but were retained as they reflect realistic scenarios.  

- **Feature Descriptions**:  
  - **Age**: Ranges from 30 to 83 years. The most frequent age range of patients is between 50-55 years.  
  - **Year of Surgery**: Operations were conducted between 1958 and 1969. The number of surgeries varied across years.  
  - **Nodes**: Represents the number of axillary lymph nodes detected. The values are highly skewed, with most patients having 0-4 nodes detected.  

- **Target Variable**:  
  - **Survival Status**:  
    - Class `0`: Survived 5 years or more (73%).  
    - Class `1`: Died within 5 years (27%).  
    - The data is imbalanced, with a higher prevalence of survivors.  

- **Insights from Univariate Analysis**:  
  - **Age**: Patients aged below 35 had better survival chances, while those above 77 had lower survival rates.  
  - **Nodes**: Patients with more than 10 nodes detected had significantly lower survival chances.  
  - **Year**: Patients operated on in 1965 had a higher proportion of mortality compared to other years.  

- **Correlations**:  
  - Weak correlation between the number of nodes and survival status (29%).  

Visualizations such as histograms, ECDF plots, and KDE plots were employed to capture patterns and highlight critical features affecting survival.  





## 📝 **RESULTS**
    
All the results to the above Questions are provided in the pdf
Haberman-Analysis(pdf)


The Haberman dataset provides valuable insights into factors affecting post-surgery survival rates for breast cancer patients. Key findings highlight that age, year of surgery, and the number of axillary lymph nodes detected significantly impact survival outcomes. While most patients survived beyond 5 years, the data imbalance necessitates careful handling during predictive modeling. This analysis lays the groundwork for building robust classification models to predict patient survival and understand the critical factors influencing outcomes.
