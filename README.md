# Airbnb Analysis Project

## Overview

This project aims to analyze Airbnb data to gain insights into pricing trends, user behavior, and property characteristics. By leveraging data science techniques and presenting the findings through a PowerBI dashboard, we aim to provide valuable information for both hosts and guests to make informed decisions.

## Table of Contents

* [Introduction](#introduction)
* [Data Sources](#data-sources)
* [Project Structure](#project-structure)
* [Analysis](#analysis)
* [PowerBI Dashboard](#powerbi-dashboard)
* [Conclusion](#conclusion)


## Introduction

Airbnb has become a global platform connecting hosts and guests in unique and diverse accommodations. This project seeks to explore and analyze various aspects of the Airbnb ecosystem, including pricing dynamics, geographical patterns, and user preferences. The findings are visualized through an interactive PowerBI dashboard.

## Data Sources

The analysis is based on publicly available Airbnb data, including information on listings, reviews, and user profiles. The dataset used in this project can be found in:

Mongo dB --> load datasets --> sample Airbnb --> listandReviews --> data

## Project Structure

**data**: Contains raw data used in the analysis extracted from Mongodb cluster.

**notebooks**: Jupyter notebooks for data preparation

**powerbi**: PowerBI dashboard file for interactive visualization.


## Analysis

The analysis covers the following key areas:

* **Data extraction:** Here we get the data from Mongodb cluster and then extract all the essential attributes from it and arrange those things in dataframe
* **Data Cleaning and Preparation:** Handling missing values, encoding categorical variables, and preparing the data for analysis.
* **Exploratory Data Analysis (EDA):** Investigating relationships between variables, identifying trends, and visualizing patterns in the Airbnb data.


## PowerBI Dashboard

An interactive PowerBI dashboard has been created to provide a dynamic and user-friendly interface for exploring the analyzed Airbnb data. The dashboard file (`airbnb_analysis_dashboard.pbix`) is available in the `powerbi` folder.

## Conclusion

In conclusion, this analysis provides valuable insights into Airbnb pricing trends, user behavior, and property characteristics. The PowerBI dashboard enhances the user experience by allowing for a more interactive exploration of the data. Hosts and guests can leverage these findings to make informed decisions and enhance their Airbnb experience.
