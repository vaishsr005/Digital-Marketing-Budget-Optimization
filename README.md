# Digital-Marketing-Budget-Optimization

The project aims to identify the optimal budget allocation for three marketing platforms - programmatic display, search, and social - to maximize profits for a Server Company. The optimization problem is solved using the SciPy Minimize function, which implements Sequential Least Squares Programming (SLSQP) algorithm. The budget allocation is calculated using audience engagement and Pay-Per-Click (PPC) and Click-Through Rate (CTR) for each channel and for each audience type.

To solve this problem, we analyzed historical campaign data to identify the factors that drive campaign performance, and formulated the problem as a non-linear programming optimization problem with budget constraints. We then used SciPy minimize function to obtain the optimal budget allocation plan.
●	Determined the Initial budget allocated for each channel with respect to the “Ad Digital Channel”.
●	Calculated the Pay-Per Click (PPC) for each channel, 
PPC = Total Cost / Total Clicks	
●	Calculated the Click-through Rate(CTR) for each Channel, 
CTR = Total Clicks/ Total Impressions
●	SciPy Minimize function is used which implements Sequential Least Squares Programming (SLSQP) algorithm. The objective function Minimize() takes in a vector x, which represents the budget allocation for each channel, and calculates the expected returns as the dot product of the click-through rate and pay-per-click values for the channels. The objective function is formulated to maximize returns for a new budget of $1 Million, using the initial budget.
●	Initial amount spent on different audience types through different channels is determined.
●	PPC and CTR is calculated for each type of audience to estimate the amount to be allocated on them through these channels.
●	The initial budget was spent the most on the audience type 2 through social channels, which resulted in less profits. 
●	Since the ads have made more impact on the audience type 1 and 5 compared to the other types, the final budget allocated for these 2 is greater than the rest for all channels. 
