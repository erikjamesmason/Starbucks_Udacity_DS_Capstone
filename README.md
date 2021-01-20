# Starbucks_Udacity_DS_Capstone

### Table of Contents 

1. [Requirements](#requirements)
2. [Description](#description)
3. [Necessary Files](#files)
4. [Conclusions](#Conclusions)
5. [Licensing](#licensing)



## Requirements<a name="requirements"></a>

- pandas
- numpy (save, load)
- math
- json
- datetime
- matplotlib
- seaborn
- plotly.express
- sklearn (various)
- imblearn (various)
- xgboost
- lightgbm
- catboost
- pickle

## Description<a name="description"></a>

The Udacity Data Science Nanodegree Starbucks Capstone project is compromised of simulated data, containing offer portfolio details, customer profile details, and transcripts of interactions from the Starbucks rewards mobile app.

The task is to combine the available datasets and determine which demographic groups respond best to which offer types.

Potential Business Questions:

What offers and offer types tend to perform well and why?
Which, if any, demographic groups can be identified in relation to responsiveness to offers?
Inversely, which offers/demographics do not perform/respond well?
If an appropriate model can be created, which metric should be addressed for optimization?

Table of Contents:
1. Introduction: 
    - Data Viewing & Exploration
    - Data Cleaning
2. EDA Visualization
3. Data Preprcessing: 1
4. Data Preprocessing: 2
5. Data Modeling

### Necessary Files<a name="files"></a>

```
- Starbucks_Capstone_notebook.html 
- Starbucks_Capstone_notebook.ipynb 
- data
  |-portfolio.json
  |-profile.json
  |-transcript.json
  |-processed_data.csv
  |-processed_data2.csv
- README.md
```

- Starbucks_Capstone_notebook.html - for ease of downloading/viewing
- Starbucks_Capstone_notebook.ipynb - for notebook review/use
- data - folder containing data and data downloads
    - -portfolio.json - contains offer id’s and metadata (reward, channels, difficulty, offer_type)
    -profile.json - contains demographic data by id(gender, age, became_member_on, income)
    -transcript.json - contains records by id for event, value, and time (recording time of this study)
    -processed_data.csv - saved state of data to skip processing
    -processed_data2.csv - saved state of data to skip processing (additional)
- README.md - you're reading it :)


### Conclusions <a name="Conclusions"></a>

Using a StackingClassifier, the model will be able to increase the efficacy to about 74% of likely responsive customers from the original amount of 38%.
I strongly believe that improvements can be made in a few areas, namely preprocessing and model fitting.

### Licensing<a name="licensing"></a>

- data sourced from Udacity and Starbucks.

Copyright 2021 Erik James Mason

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
