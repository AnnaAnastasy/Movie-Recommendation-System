# Movie Magic: Data-Driven Recommendations

## Overview
This project builds a recommendation system that leverages neural networks and content-based filtering to predict movie ratings. By analyzing user and movie features, it provides personalized recommendations, aiming to enhance user engagement with high-quality suggestions.

## Installation
Install the necessary libraries using:

```bash
pip install pandas numpy matplotlib seaborn tensorflow
```

## Dataset Download Instructions
To run this project, you’ll need to download the datasets:
- Download the dataset from [Kaggle’s Movie Dataset page](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset).
- Save the downloaded files in the same directory as the Jupyter Notebook.

## Data Preprocessing
- **Data Cleaning and Merging**: Missing values are handled, and relevant features are combined to create a consolidated dataset.
- **Feature Engineering**: User and movie embeddings are created and concatenated for input to the neural network.

## Modeling
- **Neural Network Architecture**: Utilizes user and movie embeddings fed into fully connected dense layers.
- **Training**: The model optimizes Mean Squared Error (MSE) for predicting ratings, using early stopping to prevent overfitting.
- **Evaluation**: Performance is assessed based on prediction accuracy, specifically targeting real-world recommendation accuracy.

## Results
The model provides personalized movie recommendations with an average MSE of approximately 0.03. Check the notebook for specific results and visualizations
