# TimeSeriesForecast-2018-ShinyApp

This App can be used as a simple tool to test when should a specific smoothing forecasting technique be implemented, seven models are embeded within App.

The first part presents the summary of data you choose to analyze. The user can either upload his/her own data or use the demo data inside the R package 'fma' (airpass). Then the user should choose the column of data frame that contains the data requiring analysis. The frequency of data and the beginning/ending periods of both fitting sample and hold out sample can be set afterward.

Then the user can compare different forecasting techniques by switching to different tab panels. You can creat your own training and testing set in the data summary panel by yourself, and explore the in-sample and out-sample accuracies of the model.

In case users want to upload their own data set, the suggested form of data frame is that time in the first column and observation in the second column. However, once the location of observations is consistent with the column input, the app will definitely work. (Do not forget to set the frequency in case you want to test Holt winter model!).

(1), (2), (3) from: Forecasting: principles and practice.
