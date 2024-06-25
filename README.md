# Life-Expectancy-Analysis-Project

Analytical Question
What key factors can be identified as the primary contributors to differences in life expectancy across countries?

Data Source
This project uses the Life Expectancy dataset from Kaggle, which includes various health, economic, and demographic indicators. The dataset can be accessed here.

Dataset Description
Country: Country name
Year: Year of observation
Status: Country's development status (Developed/Developing)
Life expectancy: Life expectancy in years
Adult Mortality: Adult mortality rates for both sexes (probability of dying between 15 and 60 years per 1000 population)
Infant deaths: Number of infant deaths per 1000 population
Alcohol: Per capita alcohol consumption (in litres of pure alcohol)
Percentage expenditure: Health expenditure as a percentage of GDP per capita
Hepatitis B: Hepatitis B immunization coverage among 1-year-olds (%)
Measles: Number of reported measles cases per 1000 population
BMI: Average Body Mass Index of the population
Under-five deaths: Number of under-five deaths per 1000 population
Polio: Polio immunization coverage among 1-year-olds (%)
Total expenditure: Government expenditure on health as a percentage of total government expenditure (%)
Diphtheria: Diphtheria tetanus toxoid and pertussis (DTP3) immunization coverage among 1-year-olds (%)
HIV/AIDS: Deaths per 1000 live births due to HIV/AIDS (0-4 years)
GDP: Gross Domestic Product per capita (in USD)
Population: Population of the country
Thinness 1-19 years: Prevalence of thinness among children and adolescents aged 10 to 19 (%)
Thinness 5-9 years: Prevalence of thinness among children aged 5 to 9 (%)
Income composition of resources: Human Development Index in terms of income composition (index ranging from 0 to 1)
Schooling: Average number of years of schooling
1. Introduction
This notebook focuses on identifying the critical factors influencing life expectancy and exploring variations across different countries. The goal is to analyze the dataset, perform statistical analysis, and create visualizations to highlight key insights.

Code Example
The following libraries are essential for this analysis:

python
Copy code
import pandas as pd  # Data analysis
import matplotlib.pyplot as plt  # Data visualization
import seaborn as sns  # Advanced data visualization
from sklearn.linear_model import LinearRegression  # Machine learning
from sklearn.model_selection import train_test_split  # Data splitting
from sklearn.metrics import mean_squared_error, r2_score  # Model evaluation
Load the dataset:

python
Copy code
life_expectancy_df = pd.read_csv('Life Expectancy Data.csv')
Display the first few rows of the dataset to understand its structure:

python
Copy code
life_expectancy_df.head()
Requirements
To run this project, you need the following Python libraries:

pandas
matplotlib
seaborn
scikit-learn
You can install these libraries using pip:

sh
Copy code
pip install pandas matplotlib seaborn scikit-learn
Usage
Clone the repository or download the project files.
Ensure the necessary datasets are in the project directory.
Run the Jupyter Notebook to execute the code and generate visualizations.
Conclusion
This project provides a detailed analysis of life expectancy across countries using various health, economic, and demographic indicators. By following the steps outlined, you can replicate the analysis and gain insights into the factors affecting life expectancy.
