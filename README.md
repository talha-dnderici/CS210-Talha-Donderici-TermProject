# CS210-Talha-Donderici-TermProject

This repository includes all required files related to my CS210 term project about my Letterboxd data. I scrappet my Letterboxd data from https://github.com/L-Dot/Letterboxd-list-scraper.git . Than I checked if there is a correlation btween my ratings of movies with avarage ratings of the movies in the Letterboxd. Additionally, a machine learning model is trained to predict ratings for unrated movies.

## Project Structure 

Data Processing: The initial steps involve loading the dataset, handling missing values, and encoding categorical features. The dataset includes information such as movie titles, release year, director, genres, owner ratings, average ratings, runtime, and more.

Exploratory Data Analysis (EDA): An in-depth analysis is conducted to understand the relationships between different features. Visualizations are created to highlight correlations and patterns in the data.

Model Training: A machine learning model is trained to predict movie ratings. The decision tree algorithm is used, and hyperparameters are tuned using GridSearchCV for optimal performance.
Evaluation: The trained model is evaluated on a test set, and metrics such as Mean Absolute Error (MAE) and R-squared (R2) score are calculated to assess its predictive capabilities.

## Requirements

This project requires Python 3.x and the following dependencies:

* pandas==1.3.3

* matplotlib==3.4.3

* seaborn==0.11.2

* scikit-learn==0.24.2

To install all the dependencies, use the following command in a clean virtual environment:
```bash
pip install -r requirements.txt
```
### Installing

* Copy over the repository and work in there.

### Executing program

* To execute the program, run the CS210LetterboxdProjectMainTalhaDonderici.ipynb notebook. Upon execution, users can interact with the file by providing inputs at the bottom of each code segment.

* Explore the original dataset by examining the cs210.csv file located in the repository.

* For in-depth explanations, refer to the code blocks and text blocks within the CS210LetterboxdProjectMainTalhaDonderici.ipynb notebook. Detailed information and insights are provided throughout the notebook to enhance understanding.

## TO-DO

* It's important to note that the machine learning model may require adjustments in hyperparameter tuning for optimal performance. Users are encouraged to explore and fine-tune hyperparameters based on the specific characteristics of the dataset and the desired outcomes. This involves experimenting with different parameter values to enhance the model's predictive accuracy.

  
## Authors

Talha Donderici

### References

https://github.com/L-Dot/Letterboxd-list-scraper.git for data scrapping.
