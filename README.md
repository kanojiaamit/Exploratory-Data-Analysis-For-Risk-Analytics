# Risk Analytics using Exploratory Data Analysis

This case study aims to identify patterns which indicate if a client has difficulty paying their installments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the loan are not rejected. Identification of such applicants using EDA is the aim of this case study.

 

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.


## Authors

- [@kanojiaamit](https://www.github.com/octokatherine)


## EDA Steps
- Understanding the data
- Data Cleaning
- Univariate Analysis
- Bi-variate/Multi-Variate Analysis
## Usage/Examples

```javascript
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

import warnings
warnings.filterwarnings("ignore")
```

```javascript
inp1 = pd.read_csv("application_data.csv")
inp1.head()
```
