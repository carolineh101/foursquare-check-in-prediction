# Foursquare Check-in Prediction
Predict new check-ins on Foursquare using collaborative filtering.

## Instructions
1. Download Dingqi Yang's 'User Profile Dataset' and 'Global-scale Check-in Dataset with User Social Networks' [here](https://sites.google.com/site/yangdingqi/home/foursquare-dataset) and place them in the directory of this repository.
2. Run `Processing.ipynb` to generate `gender-checkins-complete.csv` (a subset of the check-in dataset).
3. Run `Memory-Based CF.ipynb` or `matrix_factorization.ipynb` to predict check-ins.