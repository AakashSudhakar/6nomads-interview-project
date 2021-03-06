<h1 align="center">Interview Project: <i>6Nomads</i></h1>
<p align="center">
<a href="/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg"/></a>
<a href="https://docs.python.org/3/index.html"><img src="https://img.shields.io/badge/python-3.6-blue.svg"/></a>
<a href=""><img src="https://img.shields.io/github/last-commit/AakashSudhakar/6nomads-interview-project.svg?style=flat"/></a>
<a href=""><img src="https://img.shields.io/github/repo-size/AakashSudhakar/6nomads-interview-project.svg?style=flat"/></a>
<a href="https://github.com/AakashSudhakar"><img src="https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg"/></a>
</p>

---

## Description

This repository houses my data science interview project for **6Nomads**. 

My task is to run multi-class predictions off of given training and testing datasets. I am permitted to use _Python_ and _Jupyter_ technologies to create a end-to-end data pipeline including algorithms for analysis, processing, and modeling.

To conserve data security, I have not included any of the datasets in my final submission of my repository. Instead, I have included a concise tree structure to depict my project hierarchy, including the organization of my data files. 

**Please enjoy!**

## Project Hierarchy

```
6nomads-interview-project
│   README.md
│   LICENSE
│   .gitignore
│   ...
│
└───notebooks
│   │   01-exploratory-data-analysis.ipynb
│   │   02-intermediate-data-processing.ipynb
│   │   03-predictive-data-modeling.ipynb
│   
└───structures
│   │   custom_structures.py
│   │   dataset_preprocessor.py
│   │   dataset_processor.py
│   
└───data
│   │
│   └───external
│   │   │   train.csv
│   │   │   test.csv
│   │
│   └───interim
│   │   │   train_i.csv
│   │   │   test_i.csv
│   │
│   └───processed
│       │   
│       └───X
│       │   │
│       │   └───processed
│       │   │   │   train_pXp.csv
│       │   │   │   test_pXp.csv
│       │   │
│       │   └───scaled
│       │   │   │   train_pXs.csv
│       │   │   │   test_pXs.csv
│       │   │
│       │   └───reduced
│       │   │   │   train_pXr.csv
│       │   │   │   test_pXr.csv
│       │
│       └───y
│       │   │
│       │   └───processed
│       │       │   train_pyp.csv
│       │       │   test_pyp.csv
```

## Dependencies

* [NumPy](https://github.com/numpy/numpy)
* [Pandas](https://github.com/pandas-dev/pandas)
* [MatPlotLib](https://github.com/matplotlib/matplotlib)
* [SciKit-Learn](https://github.com/scikit-learn/scikit-learn)
* ~~Imbalanced-Learn~~
* ~~XGBoost~~

## License

The content of this project itself and the source code used to format and display that content are both licensed under the MIT license.

---

<p align="center">
    <a href="https://en.wikipedia.org/wiki/Love"><img src="http://ForTheBadge.com/images/badges/built-with-love.svg"/></a>
</p>

<p align="center">Constructed and documented by <strong><a href="https://linkedin.com/in/aakashsudhakar">Aakash "Kash" Sudhakar</a></strong> (2019).
</p>