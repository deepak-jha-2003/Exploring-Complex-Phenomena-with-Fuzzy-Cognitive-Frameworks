# Using Fuzzy Cognitive Maps For Multivariate Data Forecasting

## In a nutshell

[Fuzzy cognitive maps](https://en.wikipedia.org/wiki/Fuzzy_cognitive_map) can be used as a simple model for multivariate data forecasting. Reacreation of this approach in Python 3.8 yields interesting results, albeit weaker than expected. This method is tested against the [UWave](http://zhen-wang.appspot.com/rice/projects_uWave.html) time series dataset.

#### How to use the repository
 1. `dataset_instructions.txt` - explains how to set up the UWave dataset.
 2. `requirements.txt` - use for Python pip install.

#### Key project files
 1. `fcm_train.py` - trains the model and stores it in a json file.
 2. `fcm_test.py` - tests the models given in a json file.
 3. `fcm.py` - shortcut for doing both of the above.


