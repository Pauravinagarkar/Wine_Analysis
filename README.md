markdown
Copy code
# Wine Tasting Analysis

This repository contains an in-depth analysis of wine quality using various proximity measures on the `wine-quality-white-and-red.csv` dataset. The project evaluates different similarity measures to identify significant predictors of wine quality.

## Project Overview

### Proximity Measures Implemented

- **Euclidean Distance**
- **Dot Product**
- **Cosine Similarity**
- **Pearson Correlation**

### Key Features

1. **Data Preprocessing**: Standardizes the dataset to ensure fair comparison across different measures.
2. **Similarity Calculations**: Computes similarity scores between predictors and the target variable (`quality`) using various measures.
3. **Ranking Predictors**: Ranks predictors based on their similarity scores to the target variable.
4. **Visualizations**: Provides visualizations to help interpret the similarity measures and their effectiveness.

### Dataset

The dataset used is `wine-quality-white-and-red.csv`, containing wine quality data.

### Analysis

- **Association of Predictors with Quality**: Evaluates the similarity of each predictor to the `quality` column using different measures.
- **Effect of Standardization**: Compares the effect of standardizing the dataset on the similarity scores and ranking of predictors.
- **Comparison of Different Measures**: Discusses the strengths and weaknesses of each measure in identifying significant predictors.

## Getting Started

### Prerequisites

- Python 3.x
- Required libraries: pandas, numpy, scipy, scikit-learn, matplotlib

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Pauravinagarkar/Wine-Analysis.git
   cd Wine-Analysis
Install the dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Jupyter Notebook:

bash
Copy code
jupyter notebook Pauravi_nagarkar_PR1.ipynb
Usage
Data Preprocessing: Load and preprocess the dataset to remove non-numeric columns and standardize the data.
Compute Similarities: Use the provided functions to compute similarity measures for each predictor.
Rank Predictors: Rank the predictors based on their similarity scores using different measures.
Visualize Results: Generate visualizations to interpret the similarity scores and rankings.
Results
Non-Standardized Data
Top Predictors (Euclidean Distance):
Fixed Acidity
pH
Alcohol
Standardized Data
Top Predictors (Euclidean Distance):
Alcohol
Citric Acid
Free Sulfur Dioxide
Conclusion
The analysis reveals that standardization significantly affects the ranking of predictors. Alcohol consistently ranks as a top predictor across different measures, highlighting its importance in determining wine quality.

Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

License
This project is licensed under the MIT License.

Contact
Pauravi Nagarkar
Email: pnagarkar02@gmail.com
LinkedIn: Pauravi Nagarkar

