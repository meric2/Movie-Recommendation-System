# Movie Recommendation System

This project aims to provide a movie recommendation system for a user database. In the dataset utilized, there are over 45.000 movies and user votings on these movies. The project covers multiple model trainings and predictions to recommend users the movies they might like.  

## Project Overview

The key aspects of this project include:

- Exploratory data analysis on 45.000 movies to understand the structures of the movies and how they can be shaped  
- Preprocessing data by handling missing values, mixed attributes, extra columns  
- Visualizations for intuitive analysis of movie ratings, genres and other attributes   
- Feature engineering to compute necessary matrices for the models  
- Training models: User-based and Item-based Collaborative Filtering, Non-negative Matrix Factorization and Singular Value Decomposition    
- Comparing model performances and recommending movies to the user     

## Tech Stack

**Language**: Python  
**Technologies**: Pandas, Matplotlib, Seaborn, Surprise   
**Environment**: Jupyter Notebook  

## Getting Started  

### Prerequisites
- Python 3
- Jupyter Notebook

### Installation

- Clone the repository
  ```bash
  git clone https://github.com/meric2/Movie-Recommendation-System.git
  ```

- Start Jupyter notebook
  ```bash
  jupyter notebook
  ```

- Install dependencies
  ```bash
  pip install -r requirements.txt
  ```

- Download [the dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset?select=movies_metadata.csv)
- Open `recommend.ipynb` notebook and run all cells


## Usage

The given models can be trained in their section or the saved models (.pkl) can be used to produce movie recommendations.  
