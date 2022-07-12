# Feature Engineering - Imputation, Scaling, Outlier detection in stock price data


## <a id="overview"></a>Overview
This Blueprint touches upon thre of the basic steps that may be taken through the feature engineering phase of an AI pipeline. These steps are treatment of missing values by utilising the various available imputation and filtering approaches, feature scaling that will make the features AI friendly especially for algorithms that are sensitive to scale and outliers treatment including detection and algorithms to remove or re-scale. The blueprint is mainly using tools provided by scikit-learn.

## <a id="disclaimer"></a>Disclaimer
The source code presented in this project has been written by Refinitiv only for the purpose of illustrating the concepts of creating example scenarios using the Refinitiv Data Library for Python.

***Note:** To [ask questions](https://community.developers.refinitiv.com/index.html) and benefit from the learning material, I recommend you to register on the [Refinitiv Developer Community](https://developers.refinitiv.com)*

## <a name="prerequisites"></a>Prerequisites

To execute any workbook, refer to the following:

- A Refinitiv Desktop license (Refinitiv Eikon or Refinitiv Workspace) that has API access 
- Tested with Python 3.7.13
- Packages: [pandas](https://pypi.org/project/pandas/), [scikit-learn](https://pypi.org/project/scikit-learn/), [refinitiv.data](https://pypi.org/project/refinitiv-data/)
- RD Library for Python installation:  '**pip install refinitiv-data**'


  
## <a id="authors"></a>Authors
* **Marios Skevofylakas**
