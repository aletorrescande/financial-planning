## Financial Planner Considerations

The notebook contains two financial analysis tools:
1) A financial planner for emergencies, to visualize their current savings and determine if there is enough reserves for an emergency fund.
2) A financial planner for retirement that forecasts the performance of retirement portfolio in 30 years. It is done by making an Alpaca API call via the Alpaca SDK to get historical price data that is used in Monte Carlo simulations.

Libraries and dependencies:
- os
- requests
- pandas
- dotenv
- pprint
- alpaca_trade_api
- MCForecastTools

The financial-planner jupyter notebook requires you to add your API_keys in my_keys.env file for code to work.

Variables today, start_date and end_date need to be modified to the dates you want to obtain the data.

Plots can be found under graphics folder, when you run the code new ones will be generated. 

