# ⚡Predictive Process Monitoring & Bottleneck Detection in Procurement Processes using PM4Py and Machine Learning


## 📌Project Overview

This project demonstrates end-to-end process mining and predictive process analytics using the BPI Challenge 2019 procurement event logs.

The project combines:

- Process Mining (Disco + PM4Py)
- Event Log Engineering
- Predictive Process Monitoring
- Machine Learning
- Process Visualization


## 📌 Business Problem

Enterprise procurement workflows often suffer from:
- approval bottlenecks
- delayed invoice processing
- process deviations
- inefficient resource allocation

This project uses Process Mining and Machine Learning to analyze procurement event logs and predict process delays using the BPI Challenge 2019 dataset.


## 🔗 Project Workflow

1. Data preprocessing
2. Event log preparation
3. Process discovery
4. Variant analysis
5. Bottleneck analysis
6. Feature engineering
7. Predictive modeling
8. Visualization and insights


## 🏗️Project Architecture

```bash
                    BPI Challenge 2019 Dataset
                            |
                            v
                    Data Cleaning & Preparation
                            |
                            v
                    Disco Process Mining Analysis
                            |
                            v
                    PM4Py Event Log Processing
                            |
                            v
                    Feature Engineering
                            |
                            v
                    Machine Learning Models
                            |
                            v
                    Predictive Delay Analytics
                            |
                            v
                    Visualizations & Insights

```


## 🗂️Project Structure

```bash

predictive-process-monitoring/
│
├── notebooks/
│   ├── 01_event_log_preparation.ipynb
│   ├── 02_process_discovery.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_predictive_monitoring.ipynb
│   └── 05_anomaly_detection.ipynb
│
├── screenshots/
│   ├── process_mining_map.png
│   ├── bottleneck_analysis.png
|   ├── variant_analysis.png
│   └── throughput_chart
│
├── data/
│   ├── BPI_Challenge_2019.xes
|
├── models/
│   ├── lr_model.joblib
│   ├── rf_model.joblib
│
├── requirements.txt
│
└── README.md

```


## 📊Dataset

BPI Challenge 2019

The dataset contains procurement event logs with activities

- BPI Challenge 2019 Procurement Event Log

Source:
https://data.4tu.nl/articles/dataset/BPI_Challenge_2019/12715853


### Event Log Structure

| Column | Purpose |
|---|---|
| Case ID | Unique process instance |
| Activity | Process activity |
| Timestamp | Event execution time |
| Resource | Responsible user/resource |
| Vendor | Supplier information |
| Spend Area | Procurement category |
| Net Worth EUR | Financial value |
| Document Type | ERP document category |
| Company | Organizational entity |


## Process Mining with Disco

Using Fluxicon Disco:
- Imported ERP-style procurement event logs
- Generated process maps
- Identified bottlenecks
- Analyzed throughput times
- Explored process variants
- Investigated process deviations

Then screenshots Include:

process mining map
bottleneck analysis
variants analysis
throughput chart

## Process Map

![Screenshots](https://raw.githubusercontent.com/ken1711/Predictive_Process_Mining_BPI2019/main/screenshots/process_mining_map.png)

![Screenshots](https://raw.githubusercontent.com/ken1711/Predictive_Process_Mining_BPI2019/main/screenshots/bottleneck_analysis.png)

![Screenshots](https://raw.githubusercontent.com/ken1711/Predictive_Process_Mining_BPI2019/main/screenshots/variant_analysis.png)

![Screenshots](https://raw.githubusercontent.com/ken1711/Predictive_Process_Mining_BPI2019/main/screenshots/throughput_chart.png)


## 🔗Jupyter Notebooks

All data science work is documented in the notebooks listed below.

- **01 – Event Log Preparation**

![Open Notebook](https://github.com/ken1711/Predictive_Process_Mining_BPI2019/blob/main/notebooks/01_event_log_preparation.ipynb)

- **02 – Process Discovery** 

![Open Notebook](https://github.com/ken1711/Predictive_Process_Mining_BPI2019/blob/main/notebook/02_process_discovery.ipynb)

- **03 – Feature Engineering**  

![Open Notebook](https://github.com/ken1711/Predictive_Process_Mining_BPI2019/blob/main/notebooks/03_feature_engineering.ipynb)

- **04 – Predictive Monitoring**  

[Open Notebook](https://github.com/ken1711/Predictive_Process_Mining_BPI2019/blob/main/notebooks/04_predictive_monitoring.ipynb)

- **05 – Anomaly Detection** 

[Open Notebook](https://github.com/ken1711/Predictive_Process_Mining_BPI2019/blob/main/notebooks/05_anomaly_detection.ipynb)

- **06 – Predictive Analytics Mining** 

[Open Notebook](https://github.com/ken1711/Predictive_Process_Mining_BPI2019/blob/main/notebooks/predictive_Analytics_mining.ipynb)

These notebooks demonstrate the full workflow from raw data to final model.


## 🛠️Technology Stack

### Process Mining
- Disco
- PM4Py

### Programming
- Python
- Pandas
- NumPy

### Machine Learning
- Scikit-learn
- Random Forest
- Logistic Regression

### Visualization
- Matplotlib
- Seaborn


## 🧪 Future Improvements

What can be improved:

- Real-time process monitoring
- Integration with SAP APIs
- Advanced predictive process monitoring
- Interactive Power BI dashboards
- Deep learning sequence models
- Root-cause analysis automation


## 📚 References
- [Dataset](https://data.4tu.nl/articles/dataset/BPI_Challenge_2019/12715853)

- [Sciki-Learn Documentaion](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)(https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.IsolationForest.html) (https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)


## 📜 License

This project is released under the MIT License.


## 📬Contact

github: https://github.com/ken1711
