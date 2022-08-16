# Tools
The repo is for DA/ML/AI Tools.

## Initial SetUp
```
git clone $URL
cd tools
pip install -r requirements.txt
```
---
## Contents
+ [Diagrams](#Diagrams)
+ [Pandas Profiling](#Pandas-Profiling)
    
## [Diagrams](https://diagrams.mingrammer.com/)
To draw the cloud system architecture in Python code, can be easily tracked in any version control system.
It supports 6 major providers:
+ AWS
+ Azure
+ GCP
+ Kubernetes
+ Alibaba Cloud
+ Oracle Cloud

and following notes
+ On-Premise
+ Programming Languages, including Python, R
+ Frameworks

Note that the packages uses **Graphviz** to render the diagram, so you need to 
[install Graphviz](https://graphviz.gitlab.io/download/) to use diagrams.

To quick start, check the notebooks
1. [tutorials.ipynb](https://github.com/zyunsg/tools/blob/main/notebooks/diagrams/tutorials.ipynb)
2. [examples.ipynb](https://github.com/zyunsg/tools/blob/main/notebooks/diagrams/examples.ipynb)

---

## [Pandas Profiling](https://pandas-profiling.ydata.ai/docs/master/pages/getting_started/overview.html)
Easy to use for exploratory data analysis(EDA), and presented in an interactive HTML format with:
+ **Type inference**: detect the types of columns in a DataFrame
+ **Essentials**: type, unique values, indication of missing values
+ **Quantile statistics**: minimum value, Q1, median, Q3, maximum, range, interquartile range
+ **Descriptive statistics**: mean, mode, standard deviation, sum, median absolute deviation, coefficient of variation, kurtosis, skewness
+ **Most frequent and extreme values**
+ **Histograms**: categorical and numerical
+ **Correlations**: high correlation warnings, based on different correlation metrics (Spearman, Pearson, Kendall, Cramér’s V, Phik)
+ **Missing values**: through counts, matrix, heatmap and dendrograms
+ **Duplicate rows**: list of the most common duplicated rows
+ **Text analysis**: most common categories (uppercase, lowercase, separator), scripts (Latin, Cyrillic) and blocks (ASCII, Cyrilic)
+ **File and Image analysis**: file sizes, creation dates, dimensions, indication of truncated images and existance of EXIF metadata 

To quick start, check the notebooks
1. [Titanic example](https://github.com/zyunsg/tools/blob/main/notebooks/pandas_profiling/examples.ipynb)

-------