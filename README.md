# Da_project_sem5
5th Sem Data Analysis Project 
By,
  Mahesh D
  Amrutha U
  Ananth R
  Gurushankar K
  
 Dataset : New York city Airbnb dataset
 
 Rows: 48895
 Columns: 16
 
 Missing Data:
 id                                    0
name                                 16
host_id                               0
host_name                            21
neighbourhood_group                   0
neighbourhood                         0
latitude                              0
longitude                             0
room_type                             0
price                                 0
minimum_nights                        0
number_of_reviews                     0
last_review                       10052
reviews_per_month                 10052
calculated_host_listings_count        0
availability_365                      0

They data consists of outliers but are not anomalies.

There are some moderately correlated values

The following algorithms were run for price prediction:

    Model                                   R2                         RMSE
Linear Regression 			              0.5614250464940715        35.855908963518914
Lasso 					                      0.5697512321877805 	      35.81750384917525
Random forest before tuning 		      0.9428235562864818 	      35.274887454581226
Random forest after tuning 		        0.8197042319845531	      35.06256533106831
After randomSearchCV random forest  	0.8793432406972774        34.69298187093717
SGD  					                        -8.310697212984126e+43     4.935799997417089e+23
BayesianRidge  				                0.5624400611665461        35.814393419768145
PassiveAggressiveRegressor            -3.2140108748821925 	   111.144160421833 
TheilSenRegressor 			              0.5592621341690655        35.94421519821635



The following models were run for num_of_reviews:
 
 Model                                   R2                             RMSE
Linear Regression  			              0.4078951987708327  	    34.441823402491984
lasso 					                      0.4674301062827887 	      34.373425068446295
Random forest before tuning 		      0.9554129783876347  	    26.4313143472846
Random forest after tuning  		      0.8707063268752316  	    26.745506827729905
SGD  					                        -4.720333653236627e+44     9.724632387225326e+23
BayesianRidge 				                0.41072364086973934  	    34.359461867910255
PassiveAggressiveRegressor 		       -0.05391804946543388  	    45.9505025392363
TheilSenRegressor 			              0.4032850249945138  	    34.575646768194694

 
 #To rerun kernel please comment RandomisedSearchCV for time constrain


