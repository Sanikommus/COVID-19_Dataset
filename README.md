# COVID-19_Dataset

Given a dataset containing details about new COVID-19 cases recorded in India on daily
basis as a csv file (daily_covid_cases.csv). It shows the rolling 7-day average of newly
confirmed cases starting from 30th-Jan-2020 to 2-Oct-2021. Rows are indexed with dates; the first
column represents the date and the second column represents the new COVID-19 cases recorded
that day. We will use this dataset to build an autoregression (AR) model.

The Lag_In_Days code:
* Generates plots of the data with some days lag.

The AutoCorrelation code:
* Splitting the data into 65% and 35% with shuffling as off.
* Imports the Autocorrelation model from statsmodels.tsa.ar_model.
* Applys the AR model with 5-Days lag.
* Calculating RMSE and MAPE for this case.

The AR_diff_Lag_Values code:
* Applys the AR model for different values of lag days and calculates the errors.

# Input Dataset

![image](https://user-images.githubusercontent.com/119813195/228895308-59ea1cd3-da5c-4a55-9c4d-7b632c6f232d.png)


# Output

Lag in the given data: 

![image](https://user-images.githubusercontent.com/119813195/228895751-778aa8b4-4eaa-4914-9475-72e3f28cf04b.png)

![image](https://user-images.githubusercontent.com/119813195/228895948-663b17b9-e4a7-4cfc-96f8-c9db501cea45.png)

![image](https://user-images.githubusercontent.com/119813195/228896030-4c76f443-66ab-4f75-93e7-52f8b72dd29c.png)


AR model:

![image](https://user-images.githubusercontent.com/119813195/228897168-afc6ea72-c21d-4617-a92f-4a45649b7425.png)

![image](https://user-images.githubusercontent.com/119813195/228897365-69a2af3d-40ff-41f0-97e9-cff85e8ac19b.png)

![image](https://user-images.githubusercontent.com/119813195/228897474-132f7e79-b13e-455f-988b-d9b7de2e5c86.png)

AR Model for Different Lag days:

![image](https://user-images.githubusercontent.com/119813195/228898054-c6198622-2326-45a0-a7c4-bcd42ecfc7a1.png)

![image](https://user-images.githubusercontent.com/119813195/228898178-2f347c32-a2c2-468d-93e1-b51134707cd1.png)
