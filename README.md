# NLP - Employee Complaints Analysis

## Overview

This repository delves into the analysis of employee complaints using natural language processing techniques. The dataset contains valuable information about complaints, including genre, report details, employee age, role, and gender.

## Dataset Information

- **Size:** 482 entries
- **Columns:** Genre, Report, Employee Age, Employee Role, Gender
- **Genres:** Seven unique categories with 'Communication Issues' being the most prevalent.
<img width="689" alt="Screen Shot 2024-01-31 at 20 03 11" src="https://github.com/Oumaymabamoh/NLPInsightsProject/assets/134213098/df68e9f5-9269-486d-b06f-b8b0429783e4">
## Development Overview
<iframe src="[scatter_plot.html](https://raw.githubusercontent.com/Oumaymabamoh/NLPInsightsProject/master/scatter_plot.html)" width="800" height="600"></iframe>
### Data Exploration

- Import data using pandas for initial exploration.
- Visualize relationships among employee roles, ages, and genres using Plotly.

### Text Preprocessing

- Apply text preprocessing techniques:
  - Tokenization
  - Stopword removal
  - Lemmatization
  - Stemming

### Text Vectorization Techniques

- Utilize Bag of Words (BoW) and Term Frequency-Inverse Document Frequency (TF-IDF) for text vectorization.

### K-Means Clustering

- Employ K-Means clustering on BoW representation to reveal 12 distinct clusters.
<img width="1400" alt="image" src="https://github.com/Oumaymabamoh/NLPInsightsProject/assets/134213098/c2c3c466-43e4-4ce9-b4b1-4df1fcf7abc2">
<img width="1400" alt="image" src="https://github.com/Oumaymabamoh/NLPInsightsProject/assets/134213098/8f55c916-ab15-4318-a76d-29c1e153a50c">
<img width="1400" alt="image" src="https://github.com/Oumaymabamoh/NLPInsightsProject/assets/134213098/50d05221-cfff-457c-8818-dea7ed437298">
<img width="1400" alt="image" src="https://github.com/Oumaymabamoh/NLPInsightsProject/assets/134213098/79aecad9-d5d9-4c86-917d-6d5f0afcd4f1">
### Semantic Analysis: Topic Modeling
- Apply Latent Dirichlet Allocation (LDA) and Non-Negative Matrix Factorization (NMF) for topic modeling.

### Coherence Scores
- Assess model consistency and interpretability using coherence scores: LDA (0.598) and NMF (0.967).

## Results
### Assessing Vectorization Techniques
- Compare BoW and TF-IDF techniques.
- Both LDA and NMF unveil common and distinct themes.

### Prevalent Topics
- Identify topics including 'Opportunities and Growth,' 'Communication and Work-life Balance,' 'Leadership Impact,' 'Workload Management,' and 'Employee Roles and Recognition.'

## Conclusion
- The combination of BoW or TF-IDF with LDA and NMF provides a comprehensive exploration of employee complaints.
- The choice of technique depends on analytical goals and organizational objectives.

**Note:** Due to GitHub limitations, the interactive plot can be viewed by opening the HTML file locally or through online HTML preview tools.
