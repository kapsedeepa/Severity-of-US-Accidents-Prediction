**# Severity-of-US-Accidents-Prediction**
Severity of US Accidents Prediction– US countrywide traffic accident (2016-20)

**1. Datasets:**

  **_Kaggle accident dataset [1][2]_** - The dataset consists of USA countrywide car accidents for 49 states of USA from February 2016 to June 2020. This dataset has been collected    using multiple Traffic APIs in real time. It has 49 features related to weather such as wind, temperature, etc and road conditions like bump, crossing, etc. The dataset has 3.5 million records with countrywide accident dataset from 2016 to 2020.

  **_County level demographics [3] _**– Population distribution among different age groups at county level. This dataset has 79 features related to population density by year, age group, race and state. It consisted of 7.1 million records with US demographic census data around 79 features.

**2. Modelling:**
  a. Developed single-model to perform predictions on kaggle US countrywide accidents dataset.

  b. Developed single model to perform predictions on 5 states of US(CA,VA,OK,MO,KS) representing east, west, north and south regions using only kaggle US countrywide accidents    dataset.

  c. Developed single model to perform predictions on 5 states of US(CA,VA,OK,MO,KS) using both kaggle US countrywide accidents plus US demographic dataset.

  d. Developed multiple model to perform predictions on 5 states of US(CA,VA,OK,MO,KS) separately using both kaggle US countrywide accidents plus US demographic dataset.

  e. I chose to use sklearn libraries such as random forest, decision tree, logistic regression for developing models.



**References**

[1] Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, and Rajiv Ramnath. “A Countrywide Traffic Accident Dataset.”, 2019. 

[2] Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, Radu Teodorescu, and Rajiv Ramnath. "Accident Risk Prediction based on Heterogeneous Sparse Data: New Dataset and Insights." In proceedings of the 27th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems, ACM, 2019. 

[3] United States Census Bureau “County Population by characteristics: 20210-2019”,June 22, 2020.
