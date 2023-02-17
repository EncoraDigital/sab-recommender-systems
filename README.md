# Recommender System Series

This repository contains supplementary materials for the **Recommender System Series** blog posts at [Encora's Insights](https://www.encora.com/insights/all). Their goal is to give practical examples of the discussed techniques with a real-world dataset. 

## Installation

Use *pip* and *requirements.txt* to install the required libraries:

```bash
python -m pip install -r requirements.txt
```

The Notebooks were tested using Python 3.9 only, but they may work on other versions as well. The use of virtual environments is encouraged.

## Dataset

We use the **Amazon 2014 Product Review data**. You can download it in [here](http://jmcauley.ucsd.edu/data/amazon/links.html).

## How to Start

First, follow the instructions in [Preprocessing.ipynb](Preprocessing.ipynb) and then proceed to explore the other Notebooks. 

## How this project is structured

There are two main directories in this project. 

- *dataset*: Centralizes the storage of all the versions of the dataset, either raw or processed. It should contain the kcore_5.json and metadata.json files before running [Preprocessing.ipynb](Preprocessing.ipynb).
- *model*: Stores the models developed in the Notebooks for easy reuse.
