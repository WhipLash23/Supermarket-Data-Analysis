# Supermarket Dataset Analysis

## Overview

This repository contains an exploration and analysis of a supermarket transactions dataset. The goal is to uncover actionable insights to optimize business strategies aimed at improving profitability, customer satisfaction, and operational efficiency.

## Dataset Description

The dataset captures detailed information about supermarket transactions, including:

* **Invoice ID**: Unique identifier for each transaction.
* **Branch**: Supermarket branch where the transaction occurred.
* **City**: Location of the supermarket branch.
* **Customer Type**: Classification of customers (Member or Normal).
* **Gender**: Gender of the customer.
* **Product Line**: Category of products purchased (e.g., Electronics, Groceries).
* **Unit Price**: Price per unit of the product.
* **Quantity**: Number of units purchased.
* **Tax**: Tax amount applied to the transaction.
* **Total Amount**: Total cost of the transaction, including tax.
* **Payment Method**: Mode of payment (Cash, Credit Card, E-wallet).
* **Ratings**: Customer-provided rating for the transaction or service.

## Key Objectives

1. **Analyze Customer Behavior**

   * Identify trends in purchasing patterns across different product lines, customer types, and payment methods.
   * Understand demographic impacts (e.g., gender, city) on shopping preferences.

2. **Assess Business Performance**

   * Examine revenue and sales distribution across branches and product lines.
   * Determine correlations between customer ratings and product lines to highlight strengths and weaknesses.

3. **Optimize Operations**

   * Identify peak transaction times and days to inform workforce allocation and inventory management.
   * Analyze sales variability across branches for region-specific recommendations.

## Repository Structure

```
├── Superstore_modified.csv      # Raw dataset file
├── Supermarket Project.ipynb   # Jupyter notebook for analysis
├── requirements.txt             # Python dependencies
└── README.md                    # Project overview and instructions
```

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/WhipLash23/Supermarket-Data-Analysis.git
   cd Supermarket-Data-Analysis
   ```
2. **Create a virtual environment**

   ```bash
   python3 -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```
3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
2. Open `supermarket_analysis.ipynb` to run the analysis.

## License

This project is licensed under the MIT License.

---
