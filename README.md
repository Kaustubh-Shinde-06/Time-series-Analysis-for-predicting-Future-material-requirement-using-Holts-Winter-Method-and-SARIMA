# Time-series-Analysis-for-predicting-Future-material-need-using-Holts-Winter-Method-and-SARIMA

The purpose of this project is to anticipate future material need for each client based on previous orders. The Triple exponential smoothing approach (Holt-model) Winter's is one of the methods utilised, while the SARIMA (Seasonal Auto Regressive Integrated Moving Average) model is the other. In addition to seasonality and trend, the former method can capture non-seasonal trends with repeated patterns that are not random noise.

The order behaviour is used to choose between these two methods. In some cases, we find strong sesonality as well as trends. The two algorithms chosen function well with this type of data and can forecast without the need for any extra data.

To import and clean the observed data from an excel sheet, a Python functions were written. Plots are also made for each client, each material, and each client and material combination. Finally, we use existing Python modules to implement the two algorithms. These modules implement the core of the two algorithms, but we also implement the perprocessing functions that are required before the data can be fed into the algorithms. This comprises isolating only the relevant data from the complete dataset and applying autocorrelation to determine seasonality.
