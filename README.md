# Basic Steps to be performed 

1. Data Ingestion 
2. EDA of the data 
3. Preprocessing of the data 
4. model building 
5. Model eavulation 


# 1. Data Ingestion

* Import the Required Libraries: Import the required libraries such as pandas, numpy, matplotlib, seaborn, etc.

* Load the Data.

* Load the Time Series Data into a pandas dataframe.

* Set the datetime column as the index of the dataframe.

* Check the datatype of the index and convert it to datetime if necessary.


# 2.Exploratory Data Analysis 

1. Summary Statistics
- Compute summary statistics such as mean, median, mode, standard deviation, to get an overview of the data.

2. Visualize the Time Series Data
- Plot the Time Series data 

- Plot the rolling mean and rolling standard deviation of the Time Series data.
- Decompose the Time Series Data check for any trends, seasonality, and Noise.
- Plot the decomposed components to get a better understanding of the Time Series data.

3. Stationarity Check
- Check for stationarity.
- Check for stationarity of the Time Series data using the Augmented Dickey-Fuller test.

4. Check for Autocorrelation
- Plot the autocorrelation function (ACF) and partial autocorrelation function (PACF) to identify the order of the ARIMA model.

5. Outlier Detection
- Detect and handle outliers using statistical methods or machine learning techniques.

6. Check for Autocorrelation
- Plot the autocorrelation function (ACF) and partial autocorrelation function (PACF) to identify the order of the ARIMA model.



# 3.Preprocessing of the data 

1. Fill the missing values  (if present)

2. Clean the data by removing outliers (if present)

3. Convert the data into stationary if not 

4. If necessary , normalize the data 

5. Split the data into train and test 
 