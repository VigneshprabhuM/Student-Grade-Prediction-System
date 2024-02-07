# Student Grade Prediction System

## Description

This project aims to predict the final grades of Portuguese high school students to monitor their performance and enhance retention rates. It utilizes machine learning techniques, including data visualization and modeling, to provide valuable insights into students' progress and identify at-risk individuals early on.

## Project Objective

The objective of this project is to predict students' final grades and utilize the predictions to improve student retention and academic support mechanisms.

## Project Specification

This project focuses on predicting student grades and analyzing their performance to facilitate targeted interventions and enhance learning outcomes.

## System Specification

### Hardware
- Processor: Intel dual core
- Processor speed: 1.04GHz
- RAM: 1GB
- Monitor, Keyboard, Mouse

### Software
- OS: Microsoft Windows
- Language: Python
- Compiler: Google Colab

## About Dataset

### Source:
Paulo Cortez, University of Minho, Guimarães, Portugal, http://www3.dsi.uminho.pt/pcortez

### Data Set Information:
This dataset evaluates student achievement in secondary education at two Portuguese schools. It includes student grades, demographic, social, and school-related features, collected through school reports and questionnaires. Two datasets are provided for performance in Mathematics (mat) and Portuguese language (por), modeled under binary/five-level classification and regression tasks. The target attribute G3 has a strong correlation with G2 and G1, as G3 represents the final year grade while G1 and G2 correspond to the 1st and 2nd period grades, respectively.

### Attribute Information:
- **school**: Student's school ('GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)
- **sex**: Student's sex ('F' - female or 'M' - male)
- **age**: Student's age (numeric: from 15 to 22)
- **address**: Student's home address type ('U' - urban or 'R' - rural)
- **famsize**: Family size ('LE3' - less or equal to 3 or 'GT3' - greater than 3)
- **Pstatus**: Parent's cohabitation status ('T' - living together or 'A' - apart)
- **Medu**: Mother's education (0 - none, 1 - primary education, 2 - 5th to 9th grade, 3 - secondary education, 4 - higher education)
- **Fedu**: Father's education (same scale as Medu)
- **Mjob**: Mother's job ('teacher', 'health', 'services', 'at_home', or 'other')
- **Fjob**: Father's job (same categories as Mjob)
- **reason**: Reason for choosing the school ('home', 'reputation', 'course', or 'other')
- **guardian**: Student's guardian ('mother', 'father', or 'other')
- **traveltime**: Home to school travel time (1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, 4 - >1 hour)
- **studytime**: Weekly study time (1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, 4 - >10 hours)
- **failures**: Number of past class failures (n if 1<=n<3, else 4)
- **schoolsup**: Extra educational support (yes or no)
- **famsup**: Family educational support (yes or no)
- **paid**: Extra paid classes within the course subject (yes or no)
- **activities**: Extra-curricular activities (yes or no)
- **nursery**: Attended nursery school (yes or no)
- **higher**: Wants to take higher education (yes or no)
- **internet**: Internet access at home (yes or no)
- **romantic**: With a romantic relationship (yes or no)
- **famrel**: Quality of family relationships (1 - very bad to 5 - excellent)
- **freetime**: Free time after school (1 - very low to 5 - very high)
- **goout**: Going out with friends (1 - very low to 5 - very high)
- **Dalc**: Workday alcohol consumption (1 - very low to 5 - very high)
- **Walc**: Weekend alcohol consumption (1 - very low to 5 - very high)
- **health**: Current health status (1 - very bad to 5 - very good)
- **absences**: Number of school absences (0 to 93)
- **G1**: First period grade (0 to 20)
- **G2**: Second period grade (0 to 20)
- **G3**: Final grade (0 to 20, output target)



## Packages

### NumPy
- Python library for numerical computations.

### Pandas
- Python library for data manipulation and analysis.

### Matplotlib
- Python library for data visualization.

## Data Visualization

Data visualization plays a crucial role in understanding and analyzing the dataset. Some examples of visualization techniques used in this project are:

- **Visualizing the Regression Line:** Visualization of the regression line to understand the relationship between different variables.
- **Scatterplot:** Utilizing scatterplots to visualize the relationship between study time and final grades.
- **Correlation Matrix:** Displaying a correlation matrix to identify patterns and relationships between variables.
- **Residual Analysis:** Analyzing residuals to assess the fit of the regression model.

## Evaluating Model

Model evaluation is essential for understanding the performance of machine learning models. In this project, we evaluate the model using various metrics, including R-squared value, mean squared error, and mean absolute error.

