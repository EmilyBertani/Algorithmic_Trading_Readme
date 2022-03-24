# Algorithmic Trades Backtesting Strategies

---

With this project we have constructed multiple models to determine optimal algorithmic trading backtesting strategies. Once the desired models and strategies have been determined, they can be tested on various stocks of one's choosing.

---

## Technologies

---

This project utilizes Python 3.7 along with the following packages:

* [pandas](https://pandas.pydata.org/) - Python software library for data manipulation.

* [numpy](https://numpy.org/) - Fundamental packages for scientific computing with Python.

* [sklearn](https://scikit-learn.org/stable/) - Tools for predictive data analysis.

* [matplotlib](https://matplotlib.org/) - Visualization library.

* [seaborn](https://seaborn.pydata.org/) - Statistical data visualization.

* [yfinance](https://pypi.org/project/yfinance/) - Open source tool that uses Yahoo's publicly available APIs for research and education.

---

## Installation Guide

#### Data Objects

`import numpy as np`

`import pandas as pd`

`from datetime import datetime as dt, timedelta as td`

#### Plotting

`import matplotlib.pyplot as plt`

`import matplotlib.gridspec as gridspec`

#### Data Collection

`import pandas_datareader.data as pdr`

`import yfinance as yf`

#### Preprocessing and Pipeline

`from sklearn.preprocessing import RobustScaler`

`from sklearn.pipeline import Pipeline`

#### Models

`from sklearn.ensemble import RandomForestClassifier`

`from sklearn.linear_model import LogisticRegression`

```from sklearn.discriminant_analysis import(
    LinearDiscriminantAnalysis as LDA,
    QuadraticDiscriminantAnalysis as QDA
)```

`from sklearn.svm import LinearSVC, SVC`

#### Evaluation

`from sklearn.metrics import classification_report`

#### Settings

`yf.pdr_override()`

---

## Getting Started

---

## Contributors

* Josh Mischung: josh@knoasis.io // [LinkedIn]()

* Max Acheson: maxacheson@gmail.com // [LinkedIn](https://www.linkedin.com/in/max-acheson-75093a19a/)

* Emily Bertani: emily.bertani.md@gmail.com // [LinkedIn](https://www.linkedin.com/in/emily-bertani-1ab184222/)

## License

---

MIT License

Copyright (c) [2022] [Joshua Mischung, Max Acheson, Emily Bertani]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
