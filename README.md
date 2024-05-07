## Overview
This repository hosts the DS301 project focused on analyzing and clustering COVID-19 research articles. Our goal is to enhance the searchability and summarization of COVID-19 scientific literature, leveraging data-driven methods to streamline the research review process. This project can potentially benefit online academic libraries and researchers by providing quick access to relevant studies.

## Milestone 1: Project Proposal
Objective: Develop a tool using clustering algorithms to organize COVID-19 research effectively.
Motivation: Address the challenge of navigating through the vast volume of COVID-19 research articles.
Dataset: Utilizes the comprehensive CORD-19 dataset provided by the Allen Institute for AI, which includes over 400,000 scholarly articles.
Methodology: Experimentation with various clustering and text summarization methods to determine the most efficient strategy.
## Milestone 2: Midway Checkpoint
Data Processing: Essential preprocessing steps were implemented, including language detection and data cleaning to refine the dataset to English-language COVID-19 research articles.
Clustering Techniques: Evaluated multiple clustering methods (KMeans, MiniBatch KMeans, SOM, LDA) on the dataset to determine the best fit for further analysis.
Results: MiniBatch K-Means was selected for further deployment due to its efficiency and scalability.
## Milestone 3: Final Report
Deployment: Expanded the application of MiniBatch K-Means to recent data from 2020, 2021, and 2022.
Text Summarization: Integrated BERT and BART models to generate summaries for the clustered topics, aiming to provide concise representations of research themes.
Future Work: Plans to refine analysis and enhance the presentation of the findings.
## Repository Structure
/data: Contains scripts and notebooks for data preprocessing and clustering.
/models: Includes trained models for text summarization and clustering.
/docs: Documentation and milestone reports.
/results: Visualizations and summary outputs of the analyses.
