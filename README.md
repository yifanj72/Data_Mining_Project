# Data_Mining_Project
## Description
Predict the labeling of legendary Pokemons by using various features and statistics of the current list of legendary & non-legendary Pokemons.

## Data
* The data was downloaded from [Kaggle](https://www.kaggle.com/datasets/rounakbanik/pokemon).     
* The dataset contains information on all 802 Pokemon from all Seven Generations of Pokemon. This dataset contains information such as Base Stats, Performance against Other Types, Height, Weight, Classification, Egg Steps, Experience Points, Skills, etc. The file size is 161 KB before any clean-up, and there're 41 attributes.

## Methodology and Tools
* Dimensional Reduction
  * SMOTE
  * PCA
* Traditional Supervised ML Model
  * Decision Tree
  * KNN
  * Logistic Regression
  * Randome Forest
  * Linear SVC
  * Stochastic Gradient Descent
  * Gaussian Naive Bayes
  * Perceptron
* Traditional Unsupervised Learning
  * K-Means (Clustering)
  * DBSCAN
  * t-SNE
* Tools
  * Cloud Platform: Google Collaboratory
  * Data Storage: Google Drive
  
## Findings and Conclusions
* Strategy Revisited
    * By determining the best model, we can better predict if a Pokemon is legendary or not, and thus help players and game creators identify the value behind each Pokemon they choose or create.
* Lessons Learned
    * The usage of SMOTE for imbalanced datasets, and how dimensional reduction with PCA is used
    * The usage of clustering techniques like Kmeans or TSNE, to better understand the patterns of data
    * The importance of understanding the features prior to modeling specifically impacting accuracy, recall, precision and fitting problems
* Future Improvements
    * Getting inference data that are like the features within our tuned models for better overall real-world scenario examples
    * Using Pokemon statistics to predict their overall win rate percentage based on the combination of type and stats they have
    * The implementation of Gridsearch for hyper-parameter tuning for all models, to improve overall improvement in model outputs
    * Obtaining tweets and additional social media insights about each Pokemon, and create a Pokemon popularity prediction for the company to better launch apparels for their fans

## Files
* Data
  * Pokemon.csv
    * Raw data extracted from Kaggle
  * Pokemon_cleaned.csv
    * Pokemon data after initial data cleaning
  * pokemon_bin_1.csv
    * Pokemon data after applying a binning technique for certain columns
  * pokemon_inf.csv
    * Pokemon data hold for inferencial test
* Notebooks
  * Data_Cleaning.ipynb
  * PokemonClustering.ipynb
  * Pokemon_Kmeans_Clustering.ipynb
  * Pokemon_TSNE.ipynb
  * initial_EDA.ipynb
  * pokemon_model-bin1.ipynb
  * pokemon_model_1_base.ipynb
  * pokemon_model_2_Binned.ipynb
  * pokemon_model_3_Smote.ipynb
  * pokemon_model_4_PCA.ipynb
  * pokemon_model_5_PCA-Smote.ipynb
  * pokemon_Inference_PCA-Smote.ipynb
  * pokemon_Inference_Smote.ipynb
* Tableau
  * pokemon.twb
    * Stacked column chart illustrates an imbalanced distribution of data within columns
* Pokemon Presentation.pdf
