# Data Versioning and Machine Learning with LakeFS and DagsHub

This project explores data versioning and machine learning workflows using LakeFS and DagsHub, based on the **athletes dataset**. It demonstrates the use of data versioning tools for handling multiple dataset versions, building machine learning models, and comparing metrics, including incorporating differential privacy.

---

## Project Overview

### Objectives:
1. Clean the dataset and create two versions:
   - **Version 1 (v1):** Raw dataset with minimal processing.
   - **Version 2 (v2):** Enhanced dataset with outliers removed, survey responses cleaned, and new features added.
2. Perform exploratory data analysis (EDA) for both versions.
3. Build machine learning models to predict `total_lift` for both versions and compare performance metrics.
4. Implement differential privacy (DP) using TensorFlow Privacy for v2 and evaluate its impact on model performance.
5. Compare LakeFS and DagsHub for:
   - Ease of installation
   - Dataset versioning
   - Switching between dataset versions
   - Impact of DP on accuracy and metrics

---

## Features

- **Data Cleaning:**  
  Applied outlier removal, survey data cleaning, and column filtering to prepare datasets.

- **Data Versioning:**  
  Used LakeFS and DagsHub to manage and switch between dataset versions.

- **Machine Learning Models:**  
  Trained and evaluated models on v1 and v2 datasets for predicting `total_lift`.

- **Differential Privacy:**  
  Incorporated TensorFlow Privacy to evaluate the impact of DP on model metrics.

- **Tool Comparison:**  
  Analyzed and documented the strengths and challenges of using LakeFS and DagsHub for MLOps workflows.

---

## Tools Used

- **LakeFS:**  
  For dataset versioning and managing changes across data pipelines.

- **DagsHub:**  
  For version control and collaborative data science.

- **TensorFlow Privacy:**  
  To implement differential privacy in machine learning workflows.

---

## Results Summary

- **Model Performance:**
  - v1 vs. v2: Model trained on v2 outperformed v1 due to improved data quality.
  - DP vs. Non-DP: Differential privacy introduced a slight drop in accuracy but ensured data protection.

- **Tool Comparison:**
  - LakeFS: Excellent for scalability and seamless integration with S3-compatible storage.
  - DagsHub: Ideal for collaborative projects with intuitive UI and Git-based workflow.

