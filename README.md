# London Bike Sharing Prediction

### Metadata:

- <b> "timestamp" </b> - timestamp field for grouping the data
- <b> "cnt" </b> - the count of a new bike shares
- <b> "t1" </b> - real temperature in C
- <b> "t2" </b> - temperature in C "feels like"
- <b> "hum" </b> - humidity in percentage
- <b> "windspeed" </b> - wind speed in km/h
- <b> "weathercode" </b> - category of the weather
- <b> "isholiday" </b> - boolean field - 1 holiday / 0 non holiday
- <b> "isweekend" </b> - boolean field - 1 if the day is weekend
- <b> "season" </b> - category field meteorological seasons: 0-spring ; 1-summer; 2-fall; 3-winter.

- <b> "weathe_code" category description: </b>
    1 = Clear ; mostly clear but have some values with haze/fog/patches of fog/ fog in vicinity 2 = scattered clouds / few clouds 3 = Broken clouds 4 = Cloudy 7 = Rain/ light Rain shower/ Light rain 10 = rain with thunderstorm 26 = snowfall 94 = Freezing Fog
    
    
### Outline:

- <b> Observe Dataset </b>
- <b> Exploratory Data Analysis </b>
    - Missing values
    - Univariate analysis (Target Attribute)
    - Univariate analysis (Independent Attributes)
    - Multivariate analysis (Categorical & Numerical)
    - Feature Engineering
    
- <b> Dataset Preparation </b>
    - Scaling dataset
- <b> Modeling and Evaluation Metrics </b>
    - Linear Regression
    - XGBBoostRegressor
    - Lasso Regressor
