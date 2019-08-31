## **Introduction**

<p align="justify"> In this project we will explores the univariate, bivariate, & multivariate relationships between variables using Exploratory Data Analysis (EDA) techniques in R. To do so we are going to use a 
[tidy data](http://vita.had.co.nz/papers/tidy-data.pdf) 
that is created - using red wine samples - on 2009 by P.cortez and al, the dataset is related to variants of the Portuguese 
["Vinho Verde"](https://en.wikipedia.org/wiki/Vinho_Verde) wine.</p>

## **About the Dataset**
This dataset is public available for research. The details are described in [Cortez et al., 2009].

<p align="justify"> P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. 
Modeling wine preferences by data mining from physicochemical properties.
In Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.</p>

Available at:

- [Elsevier](http://dx.doi.org/10.1016/j.dss.2009.05.016)
- [Pre-press (pdf)](http://www3.dsi.uminho.pt/pcortez/winequality09.pdf)
- [bib](http://www3.dsi.uminho.pt/pcortez/dss09.bib)

### **Number of Instances**: Red Wine - 1599 obersvations 

### **Number of Attributes**: 11 + output attribute

### **Variable Description**

- **Fixed acidity**: most acids involved with wine or fixed or nonvolatile  (do not evaporate readily).
- **Volatile acidity**: the amount of acetic acid in wine, which at too high of levels can lead to an unpleasant, vinegar taste.
- **Citric acid**: found in small quantities, citric acid can add 'freshness' and flavor to wines.
- **Residual sugar**: <p align="justify"> the amount of sugar remaining after fermentation stops, it's rare to find wines with less than 1 gram/liter and wines with greater than 45 grams/liter are considered sweet.</p>
- **Chlorides**: the amount of salt in the wine.
- **Free sulfur dioxide**: <p align="justify">the free form of SO2 exists in equilibrium between molecular SO2 (as a dissolved gas) and bisulfite ion; it prevents microbial growth and the oxidation of wine.</p>
- **Total sulfur dioxide**: <p align="justify"> amount of free and bound forms of S02; in low concentrations, SO2 is mostly undetectable in wine, but at free SO2 concentrations over 50 ppm, SO2 becomes evident in the nose and taste of wine.</p>
- **Density**: the density of water is close to that of water depending on the percent alcohol and sugar content.
- **pH**: <p align="justify">describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic); most wines are between 3-4 on the pH scale.</p>
- **Sulphates**: <p align="justify">a wine additive which can contribute to sulfur dioxide gas (S02) levels, which acts as an antimicrobial and antioxidant.</p>
- **Alcohol**: the percent alcohol content of the wine.
- **Quality**: output variable (based on sensory data, score between 0 and 10).

### **Variable Information**

--  **Input variables (based on physicochemical tests):**

- fixed acidity (tartaric acid - g / dm^3)
- volatile acidity (acetic acid - g / dm^3)
- citric acid (g / dm^3)
- residual sugar (g / dm^3)
- chlorides (sodium chloride - g / dm^3
- free sulfur dioxide (mg / dm^3)
- total sulfur dioxide (mg / dm^3)
- density (g / cm^3)
- pH
- sulphates (potassium sulphate - g / dm3)
- alcohol (% by volume)

--  **Output variable (based on sensory data):**

- quality (score between 0 and 10)

## The Question we will be answering 

### Univariate Analysis :

- What is the structure of your dataset?
- What is/are the main feature(s) of interest in your dataset?
- What other features in the dataset do you think will help support your investigation into your feature(s) of interest?
- Did you create any new variables from existing variables in the dataset?
- Of the features you investigated, were there any unusual distributions? Did you perform any operations on the data to tidy, adjust, or change the form of the data? If so, why did you do this?

### Bivariate Analysis :

- Talk about some of the relationships you observed in this part of the investigation. How did the feature(s) of interest vary with other features in the dataset?
- Did you observe any interesting relationships between the other features (not the main feature(s) of interest)?
- What was the strongest relationship you found?

### Multivariate Analysis:

- Talk about some of the relationships you observed in this part of the investigation. Were there features that strengthened each other in terms of looking at your feature(s) of interest?
- Were there any interesting or surprising interactions between features?
- OPTIONAL: Did you create any models with your dataset? Discuss the strengths and limitations of your model.
