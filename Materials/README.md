# Movie Sentiment Analysis
Authors: Daria Slowinska, Carly Farrey, Isaiah Lucero

## Software & Platform
Analysis was performed using Python in a Jupyter Notebook run in both Visual Studio Code and Google Colab. Visulizations were preformed using R in R Studio.

Required Modules:
* numpy
    * install: https://numpy.org/install/
* pandas
    * install: https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html
* VADER sentiment
    * install: https://vadersentiment.readthedocs.io/en/latest/pages/installation.html
* statsmodels
    * install: https://www.statsmodels.org/dev/install.html
* scikit-learn (sklearn)
    * install: https://scikit-learn.org/stable/install.html

Required Modules (for R):
 * ggplot2
    * install: [https://scikit-learn.org/stable/install.html](https://ggplot2.tidyverse.org/)
* data.table
    * install: (https://www.rdocumentation.org/packages/data.table/versions/1.18.2.1)

Platform Used:
* MacOS, Windows

## Documentation Map
```text
project-root/
├── DATA
│   └── Data Appendix.pdf
│   └── imdb_reviews_compound.csv
│   └── imdb_sup.csv
├── OUTPUT
│   └── Final_Analysis_Output.jpeg
│   └── imdb_reviews_compound_FINAL.csv
│   └── prob_of_positive1.jpeg
│   └── prob_of_positive2.jpeg
│   └── rating_distribution.jpeg
│   └── ratings_by_sentiment.jpeg
│   └── ratings_by_sentiment2.jpeg
│   └── sentiment_d1.jpeg
│   └── sentiment_d2.jpeg
│   └── vader_compound_scores.jpeg
├── SCRIPTS
│   └── Movie_Sentiment_CODE.ipynb
│   └── plots_IMDB.Rmd
├── .gitignore
├── LICENSE
└── README.md
```

## Result Reproduction Instructions
NOTE: Instructions are also provided in Movie_Sentiment_CODE.ipynb.

1. Download the data. You can use the 'imdb_sup.csv' file in the DATA folder or download the dataset from this link: https://www.kaggle.com/datasets/nisargchodavadiya/imdb-movie-reviews-with-ratings-50k. If downloading the dataset from the Kaggle link be sure to either rename the csv to 'imdb_sup.csv' or replace all instances of 'imdb_sup.csv' with the name of the data csv in the script.
2. Download the notebook 'Movie_Sentiment_CODE.ipynb' found in the SCRIPTS folder.
3. Open the notebook in your software of choice (Jupyter Notebook, Google Colab, Visual Studio Code etc)
4. Organize the notebook ('Movie_Sentiment_CODE.ipynb') and data ('imdb_sup.csv') into the same DATA and SCRIPTS folder organization as shown in the Documentation Map. You can skip this step and simply have the notebook and data exist together is the same directory, however, for this to work you will need to make slight changes to the script. Look for the "NOTE" comments in the first two code chunks and follow the instructions. 
5. Install all necessary packages/modules (listed above). Make sure that the package are installed in the environment you will be using to run the notebook.
6. Run each code block in the notebook in order.


## References

[1] C. J. Hutto and E. Gilbert, “Welcome to VADER Sentiment’s documentation,” VADER Sentiment 3.3.1 Documentation. [Online]. Available: https://vadersentiment.readthedocs.io/en/latest/pages/introduction.html

[2] N. Chodavadiya, “IMDB Movie Reviews with ratings,” Kaggle. [Online]. Available: https://www.kaggle.com/datasets/nisargchodavadiya/imdb-movie-reviews-with-ratings-50k. [Accessed: Feb. 9, 2026].
