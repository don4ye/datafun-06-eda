# Project 6 EDA Notebook Exploratory Data Analysis with Jupyter: Planets Dataset

## Overview

Project 6 offers an opportunity to create a custom exploratory data analysis (EDA) project using GitHub, Git, Jupyter, pandas, Seaborn, and other popular data analytics tools.

## Deliverables

- **GitHub Repository**: [datafun-06-eda]
- **Documentation**: README.md
- **Notebook**:monsuru_eda.ipynb

## External Dependencies

This project will likely use at least the following external modules.

- jupyterlab
- pandas
- pyarrow
- matplotlib
- seaborn

  ## Objective

Perform and publish a custom EDA project to demonstrate skills with Jupyter, pandas, Seaborn, and popular tools for data analytics. The notebook should tell a data story and visually present findings in a clear and engaging manner.



## Environment Setup

 Create a new GitHub repository named `datafun-06-eda`.
 Clone the repository to your local machine.

Create a Project Virtual Environment in the `.venv` folder.

```bash
py -m venv .venv

Activate the Project Virtual Environment.

```bash
.\.venv\Scripts\Activate.ps1

**Install necessary packages into your project virtual environment. For example:**

```bash
py -m pip install requests


Freeze your requirements to `requirements.txt`.

```bash
py -m pip freeze > requirements.txt


# Dataset Description: Diamonds

The "diamonds" dataset contains information about various attributes of diamonds, including carat weight, cut, color, clarity, dimensions, and price. It is commonly used for data analysis and machine learning tasks in the domain of gemology and jewelry.

## Features:

1. **carat**: Weight of the diamond (measured in carats).
2. **cut**: Quality of the cut (Fair, Good, Very Good, Premium, Ideal).
3. **color**: Color of the diamond, ranging from D (colorless) to J (near colorless).
4. **clarity**: Clarity of the diamond (I1, SI2, SI1, VS2, VS1, VVS2, VVS1, IF).
5. **depth**: Total depth percentage (measured as a percentage of the diamond's height to its width).
6. **table**: Width of the top of the diamond relative to the widest point (measured as a percentage).
7. **price**: Price of the diamond (in US dollars).
8. **x**: Length of the diamond in millimeters.
9. **y**: Width of the diamond in millimeters.
10. **z**: Depth of the diamond in millimeters.

## Purpose:

The dataset is often used for exploratory data analysis (EDA), predictive modeling, and price prediction tasks. It allows analysts and researchers to understand the factors that influence the price of diamonds and to build models to predict diamond prices based on their characteristics.

## Source:

The "diamonds" dataset is available as part of the seaborn library in Python. It is commonly used in data science and machine learning tutorials, competitions, and educational materials.

# References & Acknowledgments

The analysis and information presented in this project were made possible thanks to the following resources:

- **Seaborn library**: The "diamonds" dataset used in this project was sourced from the Seaborn library, which provides a variety of datasets for data visualization and analysis in Python.

- **Python programming language**: The analysis was conducted using Python programming language, along with libraries such as Pandas, Matplotlib, and Seaborn, which are widely used in the data science community.

- **OpenAI**: Assistance and guidance provided by OpenAI's language model have greatly contributed to the development and completion of this project.
