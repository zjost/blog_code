# Overview
This example implements adversarial validation using the [IEEE Credit Card Fraud Detection dataset](https://www.kaggle.com/c/ieee-fraud-detection/data) on Kaggle.  

This code compliments an explanatory [YouTube video](https://youtu.be/7cUCDRaIZ7I) and [Blog post](https://blog.zakjost.com/post/adversarial_validation/) from Zak Jost.

# Requirements
- The [notebook](./adversarial-validation-example.ipynb) assumes you have downloaded the dataset from Kaggle and unzipped it.  
  - You'll need to update `data_dir` to point to the directory where you've extracted the data.
- See [requirements.txt](./requirements.txt) for specific versions I used
- To get the Catboost training GUI, you might need to [install/enable ipywidgets](https://catboost.ai/docs/installation/python-installation-additional-data-visualization-packages.html)
