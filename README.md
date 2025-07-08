# Deployment-Risk-Assessment-and-Rollback-Prediction

This project presents a machine learning–based system designed to assess the risk of software deployments and predict the likelihood of requiring a rollback. It also incorporates real-time monitoring of key performance metrics to detect anomalies and trigger automated rollback procedures when necessary.

### Features

* **ML-Driven Risk Assessment**: Utilizes a trained Random Forest classifier to predict rollback probability based on deployment characteristics such as code changes, test coverage, service impact, and complexity.
* **Real-Time Anomaly Detection**: Continuously monitors critical metrics like error rate, latency, and CPU usage post-deployment to identify operational issues.
* **Automated Rollback Logic**: Halts high-risk deployments or initiates rollback in response to detected anomalies.
* **Interactive Input Support**: Allows users to simulate deployment scenarios with custom input parameters.

### Repository Contents

* `deployment_dataset_5000.csv`: Synthetic dataset with 5000 deployment records for training and evaluation.
* `main.py`: Core script implementing model training, deployment simulation, monitoring, and rollback control.

### Dependencies

* Python 3.x
* pandas
* numpy
* scikit-learn
