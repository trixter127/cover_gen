---
title: Data in Machine Learning
---
Data is the cornerstone of machine learning, serving as the raw material from which models learn patterns and make predictions or decisions. Understanding the different aspects of data, from its representation to its optimization, is essential for building effective machine learning solutions.

### Key Aspects of Data

- **Representation** - How data is presented and organized for analysis.
- **Evolution** - The continuous development and changes in datasets over time.
- **Optimization** - Enhancing data quality and structure for better machine learning performance.

## Machine Learning Datasets

Machine learning datasets are crucial for training and evaluating models. They are typically categorized as follows:

- **Training Datasets** - Used for training machine learning models.
- **Validation Datasets** - Used to validate the learning process.
- **Test Datasets** - Assess the actual performance of the trained model.

## Data Ingestion

Data ingestion involves bringing data into the machine learning pipeline. Common methods include:

- Database Imports
- Data Streaming (Real-time or batches)

## Data Preparation

Preparing data is a critical step in the machine learning workflow. It includes:

- Collecting data
- Exploration and profiling of data to understand patterns
- Transformation - Formatting data for model training
- Enhancing data quality - cleaning, fixing
- Performing Feature Engineering - Normalization
- Splitting data into datasets

## Data Labeling

Data labeling is essential for supervised learning. Considerations include:

- **Accuracy vs Quality**
  - Individual items must be correct for accurate labeling.
  - Good quality labeling requires all data items to have correct labels.

## Features in Data

Features are individual characteristics or measurable properties in data. They need to be descriptive, distinctive, and independent. Key considerations include:

### Feature Selection Algorithms

- **Filter Method** - Can be used by any model.
- **Wrapper Method** - Greedy method determining which features are important.
- **Hybrid Method** - Combines features for optimal output.
- **Embedded Method** - Selects features during model training (less prone to overfitting).

### Feature Selection Techniques

- High Correlated Variables - Selecting one feature from co-related feature
- P-values - Significance of a feature
- Forward Selection - Step Wise regression , features are added as per their p value
- Backward Elimination - all features are selected and then eliminated based on p-values
- Recursive Feature Elimination - based on rank selecting exact number of features
- Variable Importance through charts - 
- Regularization - Balancing bias and variance
