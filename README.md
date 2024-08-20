# Fashion Retail Product Recommendation

## Overview
This project focuses on building a product recommendation system using a dataset of articles/products. The recommendation engine is designed to suggest similar products based on the cosine similarity of their features. The dataset has been preprocessed to ensure a balanced distribution of product types and color groups. Visualization and analysis have been carried out to better understand the data and the performance of the recommendation system.

## Description of Dataset 
The dataset used in this project is a collection of H&M fashion products and was retreived from [Kaggle](https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations) It has the following features:

* article_id
* product_code
* prod_name
* product_type_no
* product_type_name
* product_group_name
* graphical_appearance_no
* graphical_appearance_name
* colour_group_code
* colour_group_name
* perceived_colour_value_id
* perceived_colour_value_name
* perceived_colour_master_id
* perceived_colour_master_name
* department_no
* department_name
* index_code
* index_name
* index_group_no
* index_group_name
* section_no
* section_name
* garment_group_no
* garment_group_name
* detail_desc

The dataset was reduced to 15,000 products to maintain balance among product types and colors.

## Data Preprocessing
This involved removing any null or duplicate values and reducing the dataset to 15,000 records while maintaining diveisty. This was due to restrictions on computer resources.

## Explorative Analysis
This includes perfroming descriptive statisics to obtain information such as the mean and standard deviation of numerical values. It also includes generating a correlation matrix which shows the relationship between each numerical column. Bar plots where used to show the distribution and relationship between categorical values.

## Recommendation System
This recommendation system is a content-based system that uses cosine similarity to suggest similar products to a given product. The similarity is calculated based on selected features like product_type_name, colour_group_name, and others.
