# House Sales in King County, USA

This repository contains a data analysis project focused on predicting house prices in King County, USA, which includes Seattle. The dataset was collected from house sales between May 2014 and May 2015. The project uses Python libraries such as pandas, matplotlib, numpy, seaborn, and scikit-learn to manipulate, visualize, and analyze the data.

## Project Overview

The project is organized into several Python scripts, each performing a specific task:

1. `data_import.py`: This script imports the dataset and performs initial data exploration.

2. `data_wrangling.py`: This script cleans and preprocesses the data, handling missing values and outliers.

3. `exploratory_data_analysis.py`: This script performs exploratory data analysis, visualizing the data and identifying key trends and relationships.

4. `model_development.py`: This script develops a predictive model to estimate house prices based on various features.

5. `model_evaluation.py`: This script evaluates the predictive model, assessing its performance and accuracy.

## Dataset

The dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015. The dataset includes various features such as square footage, number of bedrooms, number of floors, and more.

## Methodology

The project follows a standard methodology for data analysis:

1. **Data Import**: The dataset is imported using pandas and immediately explored to understand its structure and content.

2. **Data Wrangling**: The data is then cleaned and preprocessed. This includes handling missing values and outliers, and converting categorical variables into a suitable format for analysis.

3. **Exploratory Data Analysis (EDA)**: EDA is performed to understand the data and identify key trends and relationships. This involves visualizing the data using matplotlib and seaborn, and performing statistical analysis using pandas and numpy.

4. **Model Development**: A predictive model is developed using scikit-learn. The model is trained on a subset of the data, and its performance is evaluated using the remaining data.

5. **Model Evaluation**: The performance of the model is evaluated using various metrics, such as R-squared and mean squared error. The model is refined based on these evaluations.

## Results

The project aims to predict the market price of a house given a set of features such as square footage, number of bedrooms, number of floors, and so on. The goal is to determine if it's possible to predict house prices accurately based on these features.

## How to Use

To run the project, clone the repository and run the Python scripts in the following order:

1. `data_import.py`: This script imports the dataset and performs initial data exploration.

2. `data_wrangling.py`: This script cleans and preprocesses the data, handling missing values and outliers.

3. `exploratory_data_analysis.py`: This script performs exploratory data analysis, visualizing the data and identifying key trends and relationships.

4. `model_development.py`: This script develops a predictive model to estimate house prices based on various features.

5. `model_evaluation.py`: This script evaluates the predictive model, assessing its performance and accuracy.

## Contributing

Contributions are welcome! If you find a bug or have a feature request, please open an issue. If you'd like to contribute code, please fork the repository, create a new branch, and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

This project was inspired by the Coursera course on Data Analysis with Python. The dataset used in this project was sourced from the King County website.

## References

- [Coursera: Data Analysis with Python](https://www.coursera.org/specializations/data-science-python)
- [King County House Sales](https://www.kingcounty.gov/depts/assessor/esales/esales-sale-history.aspx)
