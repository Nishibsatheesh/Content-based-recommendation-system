# Content-based-recommendation-system
## Overview

Choosing the right cosmetic products can be challenging, especially for individuals with sensitive skin. While ingredient information is available on product labels, the complex chemical lists can be difficult to interpret without expertise in skincare science. This often leads to trial-and-error purchases that may not be suitable for one’s skin type.

This project leverages data science to build a content-based recommendation system that analyzes the chemical composition of cosmetics. Using ingredient lists from 1,472 Sephora products, the system processes and compares product formulations to identify similarities.

The methodology involves tokenizing ingredient lists, converting them into a document-term matrix (DTM), and applying t-SNE (t-Distributed Stochastic Neighbor Embedding) for dimensionality reduction. This transforms high-dimensional ingredient data into a 2D visual representation, preserving similarity relationships between products.

To make the analysis interactive, Bokeh visualizations are used to display ingredient-based product clusters in a scatter plot. Users can explore product similarities, view detailed ingredient compositions, and identify alternatives that align with their skincare needs.

This project provides a valuable tool for both consumers and businesses, enabling informed product selection based on ingredient compatibility rather than trial-and-error purchases.


## Features

**Content-Based Filtering:** Recommends products based on ingredient similarity.

**Ingredient Visualization:** Uses t-SNE to project high-dimensional ingredient data into a 2D space.

**Interactive Visualizations:** Built with Bokeh for dynamic and insightful visual representations.

**Data Processing & Analysis:** Utilizes Pandas, NumPy, and Scikit-learn for data handling and machine learning.

## Technologies Used

Python

Pandas, NumPy (Data Processing)

Scikit-learn (Machine Learning & t-SNE)

Bokeh (Interactive Visualization)

## Installation

To run the project, follow these steps:

- **Clone the repository:**

```bash
git clone https://github.com/Nishibsatheesh/Content-based-recommendation-system.git
```

- **Install dependencies:**

```bash
pip install -r requirements.txt
```

**Run the project:**

- Using the Jupyter Notebook (*Recommended for visualization*)

```bash
content_recommendation.ipynb
```
- Using the Python script (*For automated execution*)

```bash
main.py
```
## Usage

- Upload the cosmetics ingredient dataset.

- The system analyzes and visualizes ingredient similarities.

- View interactive plots for ingredient relationships.

- Receive ingredient-based recommendations.
   

