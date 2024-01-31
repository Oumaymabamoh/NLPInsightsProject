<img width="689" alt="Screen Shot 2024-01-31 at 20 03 11" src="https://github.com/Oumaymabamoh/NLPInsightsProject/assets/134213098/df68e9f5-9269-486d-b06f-b8b0429783e4">
<img width="1400" alt="image" src="https://github.com/Oumaymabamoh/NLPInsightsProject/assets/134213098/c2c3c466-43e4-4ce9-b4b1-4df1fcf7abc2">
<img width="1400" alt="image" src="https://github.com/Oumaymabamoh/NLPInsightsProject/assets/134213098/8f55c916-ab15-4318-a76d-29c1e153a50c">
<img width="1400" alt="image" src="https://github.com/Oumaymabamoh/NLPInsightsProject/assets/134213098/50d05221-cfff-457c-8818-dea7ed437298">
<img width="1400" alt="image" src="https://github.com/Oumaymabamoh/NLPInsightsProject/assets/134213098/79aecad9-d5d9-4c86-917d-6d5f0afcd4f1">

Employee Complaints Analysis
This repository explores employee complaints using natural language processing techniques. The dataset contains information on various aspects of complaints, including genre, report details, employee age, role, and gender.

Data Overview
The dataset comprises 482 entries with columns such as Genre, Report, Employee Age, Employee Role, and Gender.
Seven unique genres were identified, with 'Communication Issues' being the most prevalent.
Development Phase
Text Preprocessing
Imported data using pandas and visualized relationships among employee roles, ages, and genres using Plotly.
Applied text preprocessing, including tokenization, stopword removal, lemmatization, and stemming, creating refined text columns.
Text Vectorization Techniques
Utilized Bag of Words (BoW) and TF-IDF for text vectorization, providing distinct perspectives on word representation.
K-Means Clustering
Employed K-Means clustering on BoW representation, revealing 12 distinct clusters with unique thematic emphases.
Semantic Analysis: Topic Modeling
Applied Latent Dirichlet Allocation (LDA) and Non-Negative Matrix Factorization (NMF) for topic modeling, identifying prevalent themes.
Coherence Scores
Assessed model consistency and interpretability using coherence scores: LDA (0.598) and NMF (0.967).
Assessing Vectorization Techniques and Extracting Prevalent Topics
In comparing BoW and TF-IDF, each technique offers unique insights. LDA and NMF reveal common and distinct themes, providing a nuanced understanding of employee complaints.

Results
Topics identified include 'Opportunities and Growth,' 'Communication and Work-life Balance,' 'Leadership Impact,' 'Workload Management,' and 'Employee Roles and Recognition.'
Conclusion
The combination of BoW or TF-IDF with LDA and NMF provides a comprehensive exploration of employee complaints, aiding in understanding prevalent topics. The choice depends on analytical goals and organizational objectives.
Interactive Visualization
Explore the clusters and their distribution across genres in the interactive Plotly Express bar plot saved as "scatter_plot_4.html."
Note: Due to GitHub limitations, the interactive plot can be viewed by opening the HTML file locally or through online HTML preview tools.
