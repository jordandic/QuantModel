This group project was for FIN 6392, or Fintech and Blockchain, at the University of Texas at Dallas.
This model uses some common technical factors such as RSI, MACD, and Bollinger Bands. 
An example of a big data factor used is the 10Q report sentiment data. 

To run this project, run quant_model.R in R Studio.
To skip preprocessing, stock_data_100 can be loaded by using:
stock_data <- readRDS("stock_data_100", refhook = NULL)
