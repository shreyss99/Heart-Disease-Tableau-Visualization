﻿# Heart-Disease-Tableau-Analysis

Heart diseases have been known to take a major toll of people’s lives. As a layman, we may feel that the common factors for heart related diseases are cardiac arrest or blockages. But the dataset under analysis describes multiple different medical parameters associated with the heart and their typical values. We will be analyzing the relationships between them and study the implications of changes in those parameters. In this project, we will be incorporating most trending and powerful BI tool namely Tableau.

## Steps Followed:

### Data Extraction

The dataset used for analysis is the Heart Disease dataset provided by the UCI Repository. It actually contains 76 attributes out of which only 14 are used. We will be using the Cleveland dataset.

Dataset source:
https://archive.ics.uci.edu/ml/datasets/Heart+Disease

The dataset is available is a .csv file - ‘heart_disease_dataset.csv’

### Data reprocessing

The raw dataset contains few columns with unusual values which are imputed using mean and median.
Some columns actually contain categorical data and need to be converted to numeric data.
Few columns are skewed and hence we perform normalization.

### Data Exporting

Once the data has been cleaned in the data preprocessing stage, we will export the cleaned dataset into a new file with .csv format.
The new dataset file has name - ‘preprocessed_heart_disease_dataset.csv’

### Data Loading and Modification

The clean dataset is imported into Tableau Public Desktop and we add aliases to the column values to be easy for interpreting the results.

### Data Analysis

We have made use of different aspects of Tableau like different charts, labeling, aliases, filtering, and actions based on user choice. We have created separate worksheets for each type of visualization which contains the chart and a caption as well which contains the summary of analyses drawn.

### Deployment

We have deployed the worksheets on Tableau Public Software via personal email id and credentials.
All these sheets are uploaded onto the Tableau Public Software on personal profile and this viz. is visible to public. 

The link for the worksheets is at :
https://public.tableau.com/views/HeartDiseaseDiagnosticAnalysis/AgeandChol?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link
