+++
author = "Asal Delkhosh, Prof. Sadeghian"
title = "Kaggle: a dataset of 3500 penetration testing scenarios"
date = "2023-10-01"
description = "Implementing a machine learning model for automated penetration testing."
tags = [
    "machine learning",
    "svm",
    "nbias",
    "security",
    "networks"
]
+++

This dataset contains a list of vulnerabilities and attacks sets. We gathered a list of possible layer 7 attacks on APIs and then we selected which attacks can be performed based on the given vulnerabilities.

<!--more-->

You can get this dataset in multiple versions in dest directory of the main repository.

```shell
https://github.com/ptaas-tool/dataset
```

These files are our
model dataset which we are going to work on.

```json
[
  {
    "vulnerabilities": [
      "sql raw input",
      "multi source access",
      "hardcode password"
    ],
    "attacks": [
      "sql-injection"
    ]
  }
]
```

## size

Dataset stats, based of the dest versions:

```shell
Version v0.1 (simple):
Attacks = 9, Vulnerabilities = 112, Dataset size = 500, Dataset files = 10
```

```shell
Version v0.2 (complex):
Attacks = 9, Vulnerabilities = 112, Dataset size = 1000, Dataset files = 5
```

```shell
Version v0.3 (random):
Attacks = 9, Vulnerabilities = 112, Dataset size = 1000, Dataset files = 10
```

```shell
Version v0.4 (normal):
Attacks = 8, Vulnerabilities = 112, Dataset size = 1000, Dataset files = 1
```

## contribute

In order to add new data into our dataset, run the following python script and fill the inputs:

```shell
python3 main.py 100 10 # this is the number of batches that you want to import, second is the max vulnerabilities for each batch
```
