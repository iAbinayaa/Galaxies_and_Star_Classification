# Galaxy, Star, and Quasar Classification

This project focuses on the classification of celestial objects, specifically galaxies, stars, and quasars, using machine learning models. The goal is to develop an accurate and automated system that can classify astronomical objects based on their observed features.

## Dataset
The dataset used in this project is derived from the Sloan Digital Sky Survey (SDSS) or a similar astronomical survey. It contains a collection of features such as right ascension angle, declination angle, photometric filter values (u, g, r, i, z), redshift, and other relevant properties. Each object in the dataset is labeled as either a galaxy, star, or quasar.

## Data Preprocessing
The dataset undergoes a thorough preprocessing stage to handle missing values, outliers, and ensure data quality. Feature selection and dimensionality reduction techniques are applied to extract the most informative features and enhance the classification performance.

## Machine Learning Models
Various machine learning models are employed for the classification task, including Logistic Regression, Decision Trees, Random Forests, and Support Vector Machines. These models are trained on a portion of the dataset and evaluated using appropriate performance metrics such as accuracy, precision, recall, and F1-score.

## Evaluation and Visualization
The trained models are evaluated using cross-validation techniques to assess their generalization ability. The performance of each model is analyzed, and the best-performing model is selected for final deployment. Confusion matrices, precision-recall curves, and ROC curves are generated to visualize and interpret the model's performance.

## Deployment
The selected model is deployed as a classification system capable of predicting the object class (galaxy, star, or quasar) for new observations. The system can handle real-time or batch predictions, enabling efficient classification of celestial objects in large-scale astronomical datasets.

The project aims to contribute to the field of astronomy by providing an automated and reliable approach for categorizing and studying celestial objects, opening up possibilities for further scientific research and exploration.
