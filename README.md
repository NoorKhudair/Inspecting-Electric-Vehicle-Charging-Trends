# Inspecting-Electric-Vehicle-Charging-Trends
This project analyzes data on electric vehicle (EV) charging infrastructure and sales trends over the past decade, utilizing datasets from the US Government's Alternative Fuels Data Center. The goal is to understand the growth patterns of public and private charging ports and station locations, as well as to assess EV sales over time. This analysis provides insights that can aid in strategic planning and forecasting within the EV industry.
___

### The Data
&nbsp;

`private_ev_charging.csv`

| Variable   | Description                                          |
|------------|------------------------------------------------------|
| `year` |  Year of data collection |
| `private_ports`| The number of available charging ports owned by private companies in a given year  |
| `private_station_locations`   | The number of privately owned station locations for EV charging

___

`public_ev_charging.csv`
 
| Variable   | Description                                          |
|------------|------------------------------------------------------|
| `year` |  Year of data collection  |
| `public_ports`| The number of available charging ports under public ownership in a given year  |
| `public_station_locations`   | The number of publicly owned station locations for EV charging
___

The sales information is available for each model and year in the `ev_sales.csv` file:

| Variable   | Description                                          |
|------------|------------------------------------------------------|
| `Vehicle` |  Electric vehicle model |
| `year`| Year of data collection |
| `sales`   | The number of vehicles sold in the US
