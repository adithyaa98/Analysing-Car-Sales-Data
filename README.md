## Analysing-Car-Sales-Data
#### Description: A given data set,Car_Prices.csv has certain details for various cars. These include brand, price, Audi, Mileage,
####             Engine Value, Engine Type, Registration, Year and Model.The aim is to find out how each of these parameters affects 
####             'Price' of the car. Many steps need to be taken into account. 
####                  1. Downloading the Data
####                     Using Pandas libraries, Car_Prices.csv can be downloaded and the data can be read and described.
####                  2. Cleaning the data
####                     This involves many steps including:
####                         a). Checking for high variablity
####                         b). Checking for missing values
####                        c). Checking for Skewness and removing outliers.
####                         d). Checking for incorrect values.
####                  3. Checking for non-linearity in the data and making it linear it using logrithms from numpy libraries.
####                  4. Checking for multi-collinearity between the columns and removing that using variance inflation
####                    factor from statsmodels. Any variable with vif>>6 has to be removed.
####                  5. Getting Dummy Variables: Using pandas librabries to create n-1 dummy variables for n columns.
####                  6. Scalig the data using statmodels and getting it ready for R2.
####                  7.Train the model using Linear Regression
####                  8. Testing the model to make predictions.
