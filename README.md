# Data-Cleaning-and-Feature-Engineering-On-MoviesLens-Datasets
This repository involves refining MovieLens datasets for analysis by handling missing values, removing duplicates, and creating new features. These steps optimize the dataset, enhancing its predictive power for further modeling and analysis.
# Data Cleaning and Feature Engineering on MovieLens Datasets

Welcome to the **Data Cleaning and Feature Engineering on MovieLens Datasets** project! This repository contains the code and methodology for cleaning and preprocessing MovieLens datasets to prepare them for analysis and modeling.

## Project Overview

The goal of this project is to clean and engineer features from the MovieLens datasets, which contain movie ratings and metadata. The steps include handling missing values, normalizing data, and creating new features to enhance the quality of the dataset for further analysis.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
- [Feature Engineering](#feature-engineering)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [License](#license)

## Dataset

The project uses the MovieLens datasets, which typically include:
- `movies.csv`: Contains movie metadata (e.g., movie ID, title, genres).
- `ratings.csv`: Contains user ratings for movies (e.g., user ID, movie ID, rating, timestamp).
- `tags.csv` (optional): Contains tags assigned by users to movies.

## Data Cleaning

The data cleaning process includes:
- Handling missing values.
- Removing duplicates.
- Correcting inconsistencies in data.
- Converting data types as needed.
- Filtering out irrelevant or outlier data.

## Feature Engineering

Feature engineering steps involve:
- Creating new features from existing data (e.g., extracting year from movie titles).
- Encoding categorical variables (e.g., genres).
- Normalizing and scaling numerical features.
- Aggregating user ratings to create summary statistics for each movie.

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/AryanMithbawkar/Data-Cleaning-and-Feature-Engineering-On-MoviesLens-Datasets.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Data-Cleaning-and-Feature-Engineering-On-MoviesLens-Datasets
    ```

## Dependencies

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to the creators and maintainers of the MovieLens datasets for providing valuable data for this project.
