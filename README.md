# Electricity
Exploring different RNN models forecasting electricity consumption.


![PowerGrid](https://blog.malwarebytes.com/wp-content/uploads/2018/12/electricity-900x417.jpg)

[Kaggle dataset](https://www.kaggle.com/mvianna10/germany-electricity-power-for-20062017) on Germany country-wide totals of electricity consumption, wind power production, and solar power production for 2006-2017.

This data was provided by Open Power System Data ([OPSD](https://open-power-system-data.org/)). You can find details about the origin source of this data and details about its accuracy [here](https://open-power-system-data.org/data-sources).

Electricity production and consumption are reported as daily totals in gigawatt-hours (GWh). The columns of the data file are:

* Date — The date (yyyy-mm-dd format)
* Consumption — Electricity consumption in GWh
* Wind — Wind power production in GWh
* Solar — Solar power production in GWh
* Wind+Solar — Sum of wind and solar power production in GWh

For the purpose of exploring different RNN model forecasting techniques just electricity consumption was selected.
