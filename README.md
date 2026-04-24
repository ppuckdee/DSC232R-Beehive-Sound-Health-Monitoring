# DSC232R Group Project: Data Exploration

## Dataset

**Dataset link:** [Smart Bee Colony Monitor: Clips of Beehive Sounds](https://www.kaggle.com/datasets/annajyang/beehive-sounds)

Our dataset is the **Smart Bee Colony Monitor: Clips of Beehive Sounds** dataset from Kaggle by Anna Yang. It consists of beehive audio recordings and related hive data collected from European honey bee hives in California under varying environmental and biological conditions, such as hive temperature and humidity.

The dataset is **23.21 GB**.

## Project Goal

Our objective is to develop a hive health monitoring system that classifies the overall condition of bee colonies based on audio patterns.

This project would be difficult to complete on a laptop because the dataset is very large and contains thousands of audio files that must be processed and analyzed. Distributed processing is needed because it allows the workload to be split across multiple computers, making the analysis faster and easier to manage.

## Project Members

- **Adham Kamel** — adkamel@ucsd.edu
- **Snigdha Tiwari** — sntiwari@ucsd.edu
- **Patcharapol Puckdee** — ppuckdee@ucsd.edu
- **Conner Houghtby** — choughtby@ucsd.edu

## Spark UI Access Note

We attempted to access the Spark UI from JupyterLab, but the browser returned an `ERR_CONNECTION_REFUSED` error. Because the Spark UI was not reachable from the browser, we included the SparkSession verification output as evidence that Spark was running with the configured memory and executor settings.

```text
This site can't be reached
exp-1-03.expanse.sdsc.edu refused to connect.
ERR_CONNECTION_REFUSED
