**Author:** Binnur Ersöz  
**Email:** binnurersoz@gmail.com 

## Project Overview
This project performs exploratory data analysis (EDA) on a patient treatment dataset. The analysis includes:
- Inspecting numerical and categorical columns  
- Handling missing values  
- Removing duplicate entries  
- Converting treatment and application durations to numeric format  
- Standardizing numerical features  
- Encoding categorical variables 
- Visualizing distributions, correlations, and relationships among variables  

The dataset contains 2,235 records with 13 columns related to patient information, treatments, chronic diseases, allergies, and durations.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/binnurersoz/Pusula_Binnur_Ersoz.git
   cd Pusula_Binnur_Ersoz
2. Install required Python packages:
    ```bash
    pip install pandas numpy matplotlib seaborn missingno scikit-learn
3. Place the dataset Talent_Academy_Case_DT_2025.xlsx in the project directory.
4. Run the notebook or script:
    ```bash
    jupyter notebook Pusula_Binnur_Ersöz.ipynb
    or
    python main.py
5. The code will generate visualizations and provide descriptive statistics of the dataset.

## Key Notes
- Missing values in categorical columns are filled with "Missing" using SimpleImputer.
- Duplicate rows are removed based on HastaNo, TedaviAdi, UygulamaYerleri, and UygulamaSuresi.
- Numerical features are standardized using StandardScaler.
- Categorical variables are encoded using LabelEncoder for downstream analysis.

## Visualizations Included
- Histograms and boxplots for treatment duration
- Scatter plot of treatment vs. application duration by gender
- Correlation heatmap for numerical variables
- Count plots for gender distribution
- Boxplots of treatment duration by department