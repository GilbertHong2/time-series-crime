# time-series-crime

This project is to explore the crime incident counts in Boston and model it in time, with
an emphasis on the total crime incident counts and the assault crime counts as an example of
violent crime. I developed a seasonal ARIMA and a seasonal Holt-Winters model, with the
seasonal Holt-Winters model having a better performance in forecast validation. From the
dataset, the total crime counts and assault crime counts have been stable from 2015 to 2019 with
a clear seasonal pattern but have a significant drop from the beginning of 2020. The
Holt-Winters model forecasts that the total crime count would slowly go up while maintaining a
similar level as recent years, while the assault crime count could slowly recover to pre-COVID
levels and increase rather quickly.
