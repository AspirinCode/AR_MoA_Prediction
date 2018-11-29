# SAR models for predicting the Mode of Action (MoA) for Androgen Receptor 

A quick outline of the worklow is as follows:
  - Chemical Standardization
  - Duplicates are dropped based on CID. The most recorded activity for any compounds is adopted, compounds with conflicting activity are discardrd.
  - Conventional and Docking features were generated
  - A spotcheck of 6 ML algorithms
  - Further Optimization of RF and DNN
  - Visualization of Chemical Space Using an Autoencoder
  - Analysis od chemical feamework and scaffold that may help shed light on the predictions
