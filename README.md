# risk-and-hedging

You are managing trading operations for a gas fired generation plant called Drango using CCGT technology with a capacity of 700 MW, made up from two 350 MW units.
You believe that the prices for both gas and electricity for November 2020 will be approximately the same as the prices in November 2019. The Figure and Table below show average electricity price over the peak period 8 am to 8 pm in GBP per MWh, and a daily gas price in pence per therm. Usually Drango generates only in the peak period of 8 am to 8 pm.

Drango runs at an efficiency of 50% in conversion of energy from gas to electricity. The result is that a therm of gas will produce 14.52 kWh of energy and when operating normally Drango consumes 48223 therms per hour. Drango has an existing contract for gas supply at 50 pence per therm for an average of 250,000 therms per day, with the requirement to take that amount when averaged over a month. Additional gas required will be purchased at the market price.

In addition to fuel costs, the plant costs 140,000 GBP per day to run in operating and financing costs.

1. (20%) Estimate the average daily profit over the 30-day period, assuming that market prices for gas and electricity are exactly the same as the data from November 2019.

2. (20%) Assuming that wholesale market prices for gas and electricity have the same means, and covariances as the data from November 2019 use a bivariate normal distribution to take a large sample (at least 2500 points) and use this to estimate the 95% expected shortfall for daily profit (or you can do this analytically using properties of the normal distribution).

3. (20%) Now suppose that each day there is a 4% chance that one of the generation units is unavailable (an “outage”), so that for roughly 2 weeks each year the plant is reduced to operating just one unit. On these days the plant running costs are the same as before, generation is reduced to 350 MW and fuel consumption is correspondingly halved. Assuming that outages are independent of price, estimate the 95% expected shortfall for daily profit. (A simulation approach can be used here as well.) You should also explain the approach you have used.

4. (40%) Suppose it is desired to minimize expected shortfall and the current market price for a futures contract (CFD) are £49 per MWh for peak electricity (i.e. in the period 8 am to 8 pm), and 43 pence per therm for gas. What quantities of these two contracts would you recommend buying or selling in order to minimize the 95% expected shortfall for daily profit? (Assume the same pattern of outages as in part 3.) You need to explain the method you have used to obtain your answer.

On the hub you will find a spreadsheet that gives the original data and also a method for producing samples from a bivariate normal distribution with given means and covariance structure. You will find that there are functions to do this in both R and Python.

See html output from R markdown at https://kpaganopoulos.github.io/risk-and-hedging/
