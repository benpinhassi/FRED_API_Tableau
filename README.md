# FRED_API_Tableau
Using the Federal Reserve Economic Data API and Tableau for Economic Insights.  
## Data Source
The data in this project is from the FRED website.

We use the Python 'Fredapi' module to facilitate communication with the FRED API.

The information can be obtained using an API key at no cost.

Please visit the [FRED website ](https://fred.stlouisfed.org/) for more information.

## Python - using Fredapi and Pandas modules

We used the Fredapi module to communicate with the FRED API making it easier to
pull data and obtain it as pandas series or pandas data frame.

After pulling the data we did some calculations, merged them into one data frame using joins, and clean the NaN cells.

In the end, we exported the data frame to CSV and used it in Tableau Public for visualization. The CSV file was uploaded to this repository.

## Visualization with Tableau

[Click this link for live Dashboard ](https://public.tableau.com/app/profile/ben.pinhassi/viz/US_Economic_Indicators/Dashboard1)

![Dashboard](/Dashboard.JPG)

We build a dashboard with three charts:
1. Correlation between Federal Interest Rate and CPI - The main tool of the central bank to fight inflation is raising interest rates.
2. Correlation between M2 (money supply) and CPI - After the Corona epidemic and the helicopter money used to boost the economy, now when interest rates go up and the money supply goes down it has a tremendous effect on lowering  inflation, but it usually takes around 12 months to fully take effect. 
3. Correlation between Unemployment Rate and GDP - As long as the labor market stays strong with low percentage  of unemployment, the GDP will continue to rise. The fall in GDP together with higher unemployment usually happened very fast.

## Conclusions
After examing the charts we can see that inflation should go down as the effect of the M2 starts to happen. 

The Fed may raise the interest rate above this level but it is closer stop at this level while inflation continues to go down.

The labor market data won't help us to predict a recession. This one usually goes down very fast during a recession and not before. 
