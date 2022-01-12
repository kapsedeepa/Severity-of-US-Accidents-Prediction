# Severity-of-US-Accidents-Prediction
Severity of US Accidents Prediction– US countrywide traffic accident (2016-20)

a. Developed single-model to perform predictions on kaggle US countrywide accidents dataset.
b. Developed single model to perform predictions on 5 states of US(CA,VA,OK,MO,KS) representing east, west, north and south regions using only kaggle US countrywide accidents dataset.
c. Developed single model to perform predictions on 5 states of US(CA,VA,OK,MO,KS) using both kaggle US countrywide accidents plus US demographic dataset.
d. Developed multiple model to perform predictions on 5 states of US(CA,VA,OK,MO,KS) separately using both kaggle US countrywide accidents plus US demographic dataset.
e. I chose to use sklearn libraries such as random forest, decision tree, logistic regression for developing models.


Experimental Results

Model   ||    	Data 	    ||       F1 score on test || Accuracy on test 
Model 1-RF 	On entire 5 states of US 	54.6% 	73.97% 
Model 2 -DT 	On entire 5 states of US 	27.1% 	70.7% 
Model 3 - LR 	On entire 5 states of US 	31.39% 	70.73% 
Model 4 - RF 	On entire 5 states of US + demographic census dataset 	57.3% 	74.98% 
Model 5 - DT 	On entire 5 states of US + demographic census dataset 	53.4% 	72.97% 
Model 6 - LR 	On entire 5 states of US + demographic census dataset 	38.71% 	70.3% 
Model 7- RF 	For CA state of US region accidents + demographic census dataset 	72% 	73.4% 
Model 8 - RF 	For VA state of US region accidents + demographic census dataset 	71% 	73.8% 
Model 9 - RF 	For OK state of US region accidents + demographic census dataset 	23% 	89% 
Model 10 - RF 	For KS state of US region accidents + demographic census dataset 	72.47% 	70.27% 
Model 11 - RF 	For MO state of US region accidents + demographic census dataset 	71.31% 	72.6% 
Model 12 - DT 	For CA state of US region accidents + demographic census dataset 	54% 	72.56% 
Model 13 - DT 	For VA state of US region accidents + demographic census dataset 	70.40% 	73.4% 
Model 14 - DT 	For OK state of US region accidents + demographic census dataset 	19.84% 	90.63% 
Model 15 - DT 	For KS state of US region accidents + demographic census dataset 	68.21% 	64.06% 
Model 16 - DT 	For MO state of US region accidents + demographic census dataset 	70.91% 	69.55% 

