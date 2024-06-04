```markdown
# Netflix Recommendation Engine

This project aims to develop a personalized recommendation engine for an Over-The-Top (OTT) platform or streaming service. The recommendation engine utilizes user ratings and movie metadata to suggest best-suited movies for users based on their preferences and past ratings.

## Dataset Description

The dataset comprises two files:

- **customer_ratings.txt**: Contains information about user ratings for movies, including customer IDs, movie IDs, and ratings.
- **movie_titles.csv**: Provides information about movies, including movie IDs, release years, and titles.

## Objective

The primary objective of the project is to develop a recommendation engine that:

- Creates personalized recommendations for users based on their past ratings.
- Enhances user experience by providing tailored movie suggestions aligned with individual tastes.

## Key Steps

### 1. Import Necessary Libraries
- Libraries such as Pandas, NumPy, Matplotlib, and scikit-surprise are imported for data manipulation, visualization, and model building.

### 2. Data Loading
- Load the dataset from "customer_ratings.txt" using Pandas.

### 3. Exploratory Data Analysis (EDA)
- Explore the dataset to understand its structure, shape, and data types.
- Perform feature engineering to create relevant features from existing data.

### 4. Data Cleaning and Benchmarking
- Filter out users and movies based on benchmark criteria to ensure robust analysis.
- Establish benchmarks to exclude users and movies with insufficient ratings.

### 5. Integrating 'movie_title' Column
- Merge movie title information from "movie_titles.csv" into the current dataset.

### 6. Data Visualization
- Visualize the distribution of movies released per year and per decade.
- Analyze average movie ratings over time.

### 7. Implementing a Netflix Recommendation Engine
- Utilize the scikit-surprise library to build a recommendation engine using the Singular Value Decomposition (SVD) algorithm.
- Perform cross-validation to evaluate the performance of the recommendation model.

### 8. Conclusion
- Summarize key steps, findings, and insights from the project.
- Discuss future improvements for enhancing the recommendation engine.

## Files Included
- `combined_data_1.txt`: Dataset containing user ratings for movies.(https://drive.google.com/file/d/1S3y2al6BoMGnL9KoXUtKuBz04ugPllDE/view?usp=drive_link)
- `movie_titles.csv`: Dataset providing information about movies.(https://drive.google.com/file/d/1YaMSoh476KfWVR_GdjpYr8nfLZf4DdZY/view?usp=drive_link)
- `recommendation_model.pkl`: Pickle file containing the trained recommendation model.(https://drive.google.com/file/d/1W8ijvEtHn2nDDDiPzl-hAuMIVQcko1WZ/view?usp=drive_link)
- `README.md`: Markdown file providing an overview of the project.

## Model Folder

This folder contains the trained recommendation model in a `.pkl` file format.

### Trained Recommendation Model

- **File**: [recommendation_model.pkl](https://drive.google.com/file/d/1W8ijvEtHn2nDDDiPzl-hAuMIVQcko1WZ/view?usp=drive_link)
- **Description**: The trained recommendation model using the scikit-surprise library.


## Future Improvements
- Incorporate additional features such as movie genres and user demographics.
- Explore advanced recommendation algorithms to further enhance recommendation capabilities.

## Acknowledgments
This project was inspired by the need to provide personalized movie recommendations for users of streaming platforms, enhancing their overall viewing experience. We acknowledge the valuable insights and techniques provided by the scikit-surprise library for building robust recommendation systems.
```
