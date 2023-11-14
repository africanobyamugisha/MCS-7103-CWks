<h1 style="color: green; text-align: center; font-size: 30px; font-weight: bold;">🔮 Predictive Modeling for Insurance Claims 🏦<h1/>

Welcome to the machine learning lab on Predictive Modeling for Insurance Claims.

## Explore the project through the following buttons:
[![The Python Notebook](https://img.shields.io/badge/Access%20Notebook-007bff.svg)](./Assignment%203/Predictive%20Modeling%20for%20Insurance%20Claims.ipynb)

[![Submissions Folder ](https://img.shields.io/badge/Explore%20Submissions-007bff.svg)](./Assignment%203/Submission%20Predictions)

[![Task Description](https://img.shields.io/badge/Explore%20Submissions-007bff.svg)](./Assignment%203/Assignment%20Description.pdf)

## Objective
The main goal of this project is to develop a robust predictive model for determining if a building will have an insurance claim during a specific period, based on various building characteristics. The assignment focuses on exploring and applying four machine learning algorithms: Support Vector Machine (SVM), Linear Regression, k-nearest Neighbors (KNN), and Naive Bayes. The performance of these models will be evaluated using the Area Under the Curve (AUC) metric.

## Dataset Description
The dataset comprises the following variables:

| Variable            | Description                                                                        |
|---------------------|------------------------------------------------------------------------------------|
| Customer Id         | Identification number for the Policy holder                                        |
| YearOfObservation   | Year of observation for the insured policy                                         |
| Insured_Period      | Duration of insurance policy in Olusola Insurance. (Ex: Full year insurance, Policy Duration = 1; 6 months = 0.5) |
| Residential         | Is the building a residential building or not                                       |
| Building_Painted    | Is the building painted or not (N-Painted, V-Not Painted)                           |
| Building_Fenced     | Is the building fence or not (N-Fenced, V-Not Fenced)                               |
| Garden              | Building has a garden or not (V-has garden; O-no garden)                             |
| Settlement          | Area where the building is located. (R- rural area; U- urban area)                   |
| Building Dimension  | Size of the insured building in m2                                                  |
| Building_Type       | The type of building (Type 1, 2, 3, 4)                                             |
| Date_of_Occupancy   | Date the building was first occupied                                               |
| NumberOfWindows     | Number of windows in the building                                                   |
| Geo Code            | Geographical Code of the Insured building                                           |
| Claim               | Target variable. (0: no claim, 1: at least one claim over insured period)           |

