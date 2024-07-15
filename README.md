# Data Science Lab Project

### Overview
This repository contains a benchmark of machine learning and deep learning scripts for multi-labeled topic classification on "GenericMixOfTopic" dataset. The goal of the project is to evaluate a variety of approaches to find the optimum for our task and a particular use-case described in the report.

### Repository Structure
* **DS Lab Project - Data Exploration.ipynb**: contains the results of the dataset exploration, which allows the following decisions taken in every other script.
* **random_forest_HPO.ipynb**: Implements Random Forest with TF-IDF vectorization and hyperparameters tuning (to optimize the number of trees and the maximum depth).
* **NN_from_scratch_binarized_regularized_lr1.ipynb**: Builds a deep learning model from scratch, including hyperparameters tuning.
* **Pretrained Models.ipynb**: Implements pretrained models such as BART and Universal Sentence Encoder.
* **DSL_llm.ipynb**: Implements LLMs for topic classification and uses prompt optimization.
