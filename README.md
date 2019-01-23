# Cars-Risk-Prediction
Data source: https://archive.ics.uci.edu/ml/datasets/automobile

Cars are initially assigned a risk factor symbol associated with its price. Then, if it is more risky (or less), this symbol is adjusted by moving it up (or down) the scale. Actuarians call this process "symboling". A value of +3 indicates that the auto is risky, -3 that it is probably pretty safe. 

the model implemented by neural network to predict risk results: 
Accuracy: 80.33%
	                 class precision
pred. false	            78.57%
pred. true	            80.85%

the model implemented by neural network to predict price results: 
root_mean_squared_error: 4458.640 +/- 0.000
