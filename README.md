# Enhanced-Taxi-Trip-Duration-Prediction
Enhanced Taxi Trip Duration Prediction

🛠️ Model Development Overview
To predict taxi ride durations, I followed a structured workflow:

Feature Engineering
Added informative features to enhance model learning:

pickup_month, pickup_hour, pickup_dayofyear, pickup_dayofweek

euclidean_distance (between pickup and drop-off points)

store_and_fwd_flag (encoded)

Target Transformation
The target variable (trip_duration) was highly skewed, so I applied log1p transformation to stabilize variance and improve model performance.

Modeling

Used Polynomial Features to capture non-linear relationships.

Applied MinMaxScaler to normalize feature ranges.

Trained a Ridge Regression model for regularized linear prediction.

Evaluation
Achieved:

Reasonable R² score on both training and validation sets.

Better generalization due to regularization and engineered features.

⚙️ Technologies Used
Python, Scikit-learn, NumPy, Pandas

Ridge Regression, Polynomial Features, Feature Scaling


