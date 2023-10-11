# PeerAnalysis

# Projet de troisième année 2023-2024

## Entreprise: Meta-Modeling

### Overview
Meta-Modeling is a French start-up that specializes on the development of software for financial decision making. We aim to incorporate financial data-driven decisions within custom financial models to ease the work of financial analysists around the world and combine efficient data management and modeling with advanced financial analysis-based models.
## Project Theme
A school project to find a solution for corporate finance professionals to simplify the peer analysis process during companies’ valuation and during stock screening process.

## Context
- **Application Features:**
    - Stock data filtering based on various criteria.
    - Manual peer group construction for valuation metric calculation.
    - Real-time data through APIs.
    [Add more points if needed]

## Objectives

*
*
*

### Project Decomposition:
1. **Data Gathering and Database Connection:**
    - Gather pertinent data via our API and connect directly to a MongoDB database containing companies' information that we will provide. This database serves as the primary data source for the analysis.
2. **Data Preprocessing:**
    - Clean and preprocess the financial data obtained from the database to handle missing values, outliers, and format inconsistencies. Ensuring data quality is crucial for accurate analysis.
3. **Business Description Preprocessing:**
    - Preprocess the business descriptions by tokenizing, removing stop words, and applying text normalization techniques. This step prepares the textual data for further analysis.
4. **Feature Extraction:**
    - Extract numerical features from the preprocessed business descriptions using techniques like TF-IDF (Term Frequency-Inverse Document Frequency) or word embeddings. This step converts the text data into a numerical format suitable for analysis.
5. **Distance Measure Calculation:**
    - For a given set of selection criteria for the analyzed company (specified by the end user), calculate a pertinent distance measure that allows computing the distance between the analyzed company and the companies in our database. The distance measure should take into account both financial metrics and business descriptions to capture the similarity between companies.
6. **Distance Metric Selection:**
    - 	Choose an appropriate distance metric to quantify the similarity between companies based on their financial metrics and business descriptions. Common distance metrics include Euclidean distance, Cosine similarity, Jaccard similarity, etc.
7. **Peer Analysis:**
    - 	For each company, calculate the distance to the target company based on their valuation metrics and business description features using the chosen distance metric.

## Expected Deliverables
The coding will be done by the means of Python, and we would like to have a documented model to facilitate its incorporation within our solution. 
## Technology Stack
- **Programming Language:** Python
- **Database:** MongoDB
- **Libraries:** 
- **Platform:** Google Colab

## How to Use

## License

## Contact Information
Mohamed Didi, Mohamed.didi@centrale-marseille.fr
Romain Marlet, romain.marlet@centrale-med.fr
