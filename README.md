# Codon Usage Analysis

## Introduction

In molecular biology, codons are sequences of three nucleotides within DNA or RNA that correspond to specific amino acids or stop signals during protein synthesis. Each gene's sequence of codons is translated by the ribosome into a chain of amino acids, forming proteins essential to life. Codon usage refers to the frequency with which different codons encode the same amino acid and varies across species, reflecting evolutionary adaptation and gene expression preferences in different organisms.

This project aims to leverage codon usage frequencies to **predict the Kingdom and DNA type** of a species. Using the relative abundance of codons across species, we can gain insights into their biological classification. **Our approach involves analyzing codon frequencies and training a predictive model to classify species by Kingdom and DNA type based on these patterns.**

## Authors

- **[Yubraj Niraula](https://github.com/yubrajniraula)** 
- **[Aron Sbhatu](https://github.com/ASD-Are)** 

## Dataset

This analysis uses the Codon Usage dataset, available from the UCI Machine Learning Repository. Download the dataset from the following link and place it in the project directory:

[Codon Usage Dataset - UCI](https://archive.ics.uci.edu/dataset/577/codon+usage)

The dataset contains codon frequency data across various species, providing the foundation for the predictive modeling.

## Requirements

The following libraries are required for this project:

- `Pandas` - Data manipulation and analysis
- `NumPy` - Numerical computations
- `Matplotlib` and `Seaborn` - Data visualization
- `scikit-learn` - Machine learning tools for classification and preprocessing

Install the dependencies by running:
```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn
```

## Project Structure

The notebook, `Codon_usage_final.ipynb`, is organized as follows:

1. **Introduction** - Overview of codon usage and its biological significance.
2. **Data Loading and Preprocessing** - Loads the dataset, applies necessary cleaning, and prepares it for analysis.
3. **Exploratory Data Analysis (EDA)** - Visual exploration of codon usage frequencies to identify trends and patterns.
4. **Predictive Modeling** - Trains a machine learning model to classify species by Kingdom and DNA type based on codon usage frequency.
5. **Results and Visualization** - Presents the model’s classification accuracy and visualizes the results, including confusion matrices and feature importances.
6. **Conclusion** - Summarizes the findings and their implications for understanding codon usage patterns.

## Running the Analysis

1. Clone the repository:
   ```bash
   git clone https://github.com/yubrajniraula/ML-Project-on-Codon-Usage-Frequency/tree/main
   cd ML-Project-on-Codon-Usage-Frequency/tree/main
   ```

2. Download the Codon Usage dataset from the UCI link provided above, and place it in the root directory of the project.

3. Open the notebook in Jupyter:
   ```bash
   jupyter notebook Codon_usage_final.ipynb
   ```

4. Run each cell sequentially to execute data loading, analysis, and modeling.

## Results

The output of this notebook includes:
- **Model Performance Metrics** - Accuracy, precision, and recall for Kingdom and DNA type prediction.
- **Feature Importance Analysis** - Highlights which codons or groups of codons are most informative for predicting the classification.
- **Visualization** - Confusion matrices and plots for understanding classification performance.

## License

The Codon Usage dataset used in this project is licensed under a [Creative Commons Attribution 4.0 International (CC BY 4.0) license](https://creativecommons.org/licenses/by/4.0/). This permits sharing and adapting the dataset for any purpose, provided appropriate credit is given to the original source.
