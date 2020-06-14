# Identifying-Customer-Segments:

In this project, Bertelsmann partners AZ Direct and Arvato Financial Solutions have provided two datasets one with demographic information about the people of Germany, and one with that same information for customers of a mail-order sales company. I have looked at relationships between demographics features, organized the population into clusters, and saw how prevalent customers are in each of the segments obtained.

## Project Overview:
The main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign. I used unsupervised learning techniques to organize the general population into clusters, then use those clusters to see which of them comprise the main user base for the company. Prior to applying the machine learning methods, I also assessed and cleaned the data in order to convert the data into a usable form.

## Installaions:
This project uses Python 3 and is designed to be completed through the Jupyter Notebooks IDE. It is highly recommended that you use the Anaconda distribution to install Python, since the distribution includes all necessary Python libraries as well as Jupyter Notebooks. The following libraries are expected to be used in this project:

- NumPy
- Pandas
- Sklearn / scikit-learn
- Matplotlib (for data visualization)
- Seaborn (for data visualization)

## The Data :

- Udacity_AZDIAS_Subset.csv: Demographic data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
- Udacity_CUSTOMERS_Subset.csv: Demographic data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
- Data_Dictionary.md: Information file about the features in the provided datasets.
- AZDIAS_Feature_Summary.csv: Summary of feature attributes for demographic data.
