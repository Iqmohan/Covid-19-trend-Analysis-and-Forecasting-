# Covid-19-trend-Analysis-and-Forecasting-
COVID 19 Analysis on recovered, deaths, confirmed, active cases and Forecasting on the same

Covid-19-trend-Analysis-and-Forecasting-
FB Prophet Algorithm
step 1 : pandas to read a CSV file named "covid_19_clean_complete.csv" into a DataFrame

step 2: df["confirmed"] - df["deaths"] - df["recovered"]: This performs element-wise subtraction in pandas, subtracting the number of deaths and the number of recovered cases from the total number of confirmed cases for each entry. The result is the number of active cases, representing individuals who are currently infected with COVID-19 and have not yet recovered or died.

step 3: Fetch countries having most active cases in any particular date.
Step 4: Countries with Active Cases

![image](https://github.com/Iqmohan/Covid-19-trend-Analysis-and-Forecasting-/assets/159016465/3cce27e1-0649-4bdd-97db-868de8e63354)
 
step 5: Countries with confirmed Cases

![image](https://github.com/Iqmohan/Covid-19-trend-Analysis-and-Forecasting-/assets/159016465/db4e038c-ede3-4e8c-89b0-35772cb73262)


step 6: world wide confirmed cases over time
![image](https://github.com/Iqmohan/Covid-19-trend-Analysis-and-Forecasting-/assets/159016465/941ca93b-1f91-458c-ad36-3a6d12b75679)

step 7 : Death cases over time
![image](https://github.com/Iqmohan/Covid-19-trend-Analysis-and-Forecasting-/assets/159016465/e346713a-ae67-4684-853a-d2f2834be536)

step 8: most active cases
![Uploading image.png…]()

step 9 : 7 day forecasts for confirmed cases
![Uploading image.png…]()




