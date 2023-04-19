# Breast Cancer Prediction

The dataset is downloaded from [Kaggle](https://www.kaggle.com/datasets/vijayaadithyanvg/breast-cancer-prediction). It has 30 features, 1 label (diagnosis) which contains data about the patient if the cancer is benign, or malignant (cancer) and 569 samples. Some descriptive statistics can be found in the below table.


|                         | count | min      | mean       | std        | max     |
|-------------------------|-------|----------|------------|------------|---------|
| diagnosis               | 569   | nan      | nan        | nan        | nan     |
| radius_mean             | 569   | 6.981    | 14.127292  | 3.524049   | 28.11   |
| texture_mean            | 569   | 9.71     | 19.296678  | 4.301816   | 39.28   |
| perimeter_mean          | 569   | 43.79    | 91.969033  | 24.298981  | 188.5   |
| area_mean               | 569   | 143.5    | 654.889104 | 351.914129 | 2501.0  |
| smoothness_mean         | 569   | 0.05263  | 0.09636    | 0.014064   | 0.1634  |
| compactness_mean        | 569   | 0.01938  | 0.104341   | 0.052813   | 0.3454  |
| concavity_mean          | 569   | 0.0      | 0.088799   | 0.07972    | 0.4268  |
| concave points_mean     | 569   | 0.0      | 0.048919   | 0.038803   | 0.2012  |
| symmetry_mean           | 569   | 0.106    | 0.181162   | 0.027414   | 0.304   |
| fractal_dimension_mean  | 569   | 0.04996  | 0.062798   | 0.00706    | 0.09744 |
| radius_se               | 569   | 0.1115   | 0.405172   | 0.277313   | 2.873   |
| texture_se              | 569   | 0.3602   | 1.216853   | 0.551648   | 4.885   |
| perimeter_se            | 569   | 0.757    | 2.866059   | 2.021855   | 21.98   |
| area_se                 | 569   | 6.802    | 40.337079  | 45.491006  | 542.2   |
| smoothness_se           | 569   | 0.001713 | 0.007041   | 0.003003   | 0.03113 |
| compactness_se          | 569   | 0.002252 | 0.025478   | 0.017908   | 0.1354  |
| concavity_se            | 569   | 0.0      | 0.031894   | 0.030186   | 0.396   |
| concave points_se       | 569   | 0.05279  | 0.011796   | 0.00617    | 0.0     |
| symmetry_se             | 569   | 0.07895  | 0.020542   | 0.008266   | 0.007882|
| fractal_dimension_se    | 569   | 0.02984  | 0.003795   | 0.002646   | 0.000895|
| radius_worst            | 569   | 36.04    | 16.26919   | 4.833242   | 7.93    |
| texture_worst           | 569   | 49.54    | 25.677223  | 6.146258   | 12.02   |
| perimeter_worst         | 569   | 251.2    | 107.261213 | 33.602542  | 50.41   |
| area_worst              | 569   | 4254.0   | 880.583128 | 569.356993 | 185.2   |
| smoothness_worst        | 569   | 0.2226   | 0.132369   | 0.022832   | 0.07117 |
| compactness_worst       | 569   | 1.058    | 0.254265   | 0.157336   | 0.02729 |
| concavity_worst         | 569   | 1.252    | 0.272188   | 0.208624   | 0.0     |
| concave points_worst    | 569   | 0.291    | 0.114606   | 0.065732   | 0.0     |
| symmetry_worst          | 569   | 0.6638   | 0.290076   | 0.061867   | 0.1565  |
| fractal_dimension_worst | 569   | 0.2075   | 0.083946   | 0.018061   | 0.05504 |

