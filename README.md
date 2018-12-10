# ehr-big-data

Image processing tool for Electronic Health Records (EHR) using Spark, HDFS, Tesseract, and ElasticSearch



# Setup
1. Clone this repo
2. Import and activate the conda environment. All following steps must be done in this environment.

```bash
conda env create -f environment.yml
source activate ehr-big-data
```


# EAST Example
```bash

python text_detection.py --image examples/images/example_09.jpg --east frozen_east_text_detection.pb
```
