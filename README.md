# Machine Learning & Data Science Portfolio

Welcome to my Machine Learning and Data Science repository! This collection of Jupyter notebooks showcases a comprehensive journey from fundamental data preprocessing and Exploratory Data Analysis (EDA) to advanced machine learning algorithms and optimization techniques built from scratch.

---

## Repository Structure & Notebooks

### 1. Data Gathering & Exploration
* `understanding-the-data.ipynb` - Initial inspection of dataset structures, shapes, and data types.
* `pandas-profiling.ipynb` - Automated EDA generating comprehensive data profiling reports.
* `web-scrapping-using-pandas-df.ipynb` - Extracting web data and structuring it into Pandas DataFrames.
* `working-with-csv-File.ipynb` - Loading, parsing, and inspecting CSV datasets.
* `api-to-dataframe.ipynb` & `data_extractor.ipyn` - Pulling data via APIs and data extraction scripts.

### 2. Data Preprocessing & Missing Value Handling
* `complete-case-analysis.ipynb` - Analyzing and handling missing data by dropping incomplete rows.
* `imputing-numerical-data.ipynb` - Techniques for imputing missing numerical values (mean, median, arbitrary).
* `missing-categorical-imputation.ipynb` - Handling missing categorical variables.
* `missing-indicator.ipynb` - Adding missing indicators to preserve missingness information.
* `iterative-imputer.ipynb` & `knn-imputer.ipynb` - Advanced multivariate and KNN-based imputation.
* `handling-date-time.ipynb` & `handling-mixed-varible.ipynb` - Parsing timestamps, date components, and mixed data types.

### 3. Feature Engineering & Encoding
* `ordinal-encoding.ipynb` - Encoding ordered categorical features.
* `one-hot-encoding.ipynb` & `one-hot-encoding(1).ipynb` - Transforming categorical variables into binary dummy columns.
* `binarization.ipynb` - Converting continuous features into binary thresholds.
* `feature-construction-and-feature-splitting.ipynb` - Creating new informative features and splitting existing ones.
* `column-transformer.ipynb` - Applying distinct preprocessing pipelines to different columns simultaneously.

### 4. Feature Scaling & Transformations
* `normalization.ipynb` - Rescaling features to a standard range (e.g., Min-Max scaling).
* `standardization.ipynb` - Centering features to zero mean and unit variance.
* `power-transformer.ipynb` - Applying Box-Cox and Yeo-Johnson transformations for normality.
* `function-transformer.ipynb` - Applying custom mathematical functions to features.

### 5. Outlier Detection & Dimensionality Reduction
* `outlier-detection-using-percentiles.ipynb` - Identifying outliers using upper and lower percentile cutoffs.
* `outlier-removal-using-iqr-method.ipynb` - Interquartile Range (IQR) based outlier removal.
* `outlier-removal-using-zscore.ipynb` - Z-Score based anomaly and outlier detection.
* `principle-component-analysis.ipynb` - Dimensionality reduction using PCA.

### 6. Exploratory Data Analysis (EDA)
* `univariate-analysis.ipynb` - Analyzing distributions of single variables.
* `bivariate-analysis.ipynb` - Exploring relationships between pairs of features.

### 7. Optimization & Gradient Descent (From Scratch)
* `batch-gradient-descent.ipynb` - Standard batch gradient descent implementation.
* `stochastic-gradient-descent.ipynb` - Stochastic gradient descent for iterative updates.
* `mini-batch-gradient-descent-from-scratch.ipynb` - Mini-batch implementation for efficiency.
* `gradient-descent-from-scratch.ipynb` & animations (`-animation` notebooks) - Visualizing gradient descent convergence paths.

### 8. Supervised Learning & Regression/Classification
* `day48-simple-linear-regression.ipynb` - Simple linear regression modeling.
* `multiple-linear-regression.ipynb` - Multivariable regression analysis.
* `polynomial-regression.ipynb` - Non-linear modeling with polynomial features.
* `regression-metrics.ipynb` - Evaluating regression models (MSE, RMSE, $R^2$ score).
* `01_age_classification.ipynb` - Classification model for predicting age groups.
* `end-to-end-ml.ipynb` - Complete end-to-end machine learning pipeline from raw data to model deployment.

### 9. Natural Language Processing (NLP) & Text Mining
* `Text-Prepossessing-NLP.ipynb` - Tokenization, stemming, lemmatization, and stopword removal.
* `Text-Classification.ipynb` - Text classification models using NLP features.
* `word-to-vector.ipynb` - Word embeddings and vector representations.
* `Parts-of-Speech-Tagging.ipynb` - POS tagging for linguistic analysis.
* `cross-dialect.ipynb` - Handling cross-dialect text data.

### 10. Advanced & Specialized Topics
* `Multi-Scale-Physics-Informed-Neural-Network.ipynb` - PINNs combining neural networks with physical laws.
* `knowledge_graph_builder.ipynb` & `survival_knowledge_graph.ipynb` - Constructing and analyzing knowledge graphs.
* `chatbot_rules.ipynb` & `rule_engine.ipynb` - Rule-based conversational agents and expert systems.
* `unity_communication_server.ipynb` & `visual-mode-addaptation.ipynb` - External simulation and visualization tools.

---

## Technologies & Libraries Used

* **Languages:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn, SciPy
* **Deep Learning & Neural Networks:** TensorFlow / PyTorch (for PINNs)
* **NLP:** NLTK, spaCy, Gensim

---
## Getting Started

Clone the repository and explore individual notebooks in Jupyter Lab or Visual Studio Code:

```bash
git clone https://github.com/your-username/ml-portfolio.git
cd ml-portfolio
jupyter lab
```
