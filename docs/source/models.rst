Models
=====

pyfbad.models.IsolationForestModel
----------------------------------
That model includes classic Isolation Forest (IF) Model. It has **train_model()** method

   >>> train_model(self, df_model, contamination_value=float(0.06)) 
It has default contamination value (float(0.06)) and it trains the model and make prediction with given dataframe.

pyfbad.models.LocalOutlierFactorModel
--------------------------------------
That model includes classic Isolation Forest (IF) Model. It has **train_model()** method

   >>> train_model(self, df_model, contamination_value=float(0.06)) 
It has default contamination value (float(0.06)) and it trains the model and make prediction with given dataframe.

pyfbad.models.ProphetModel
---------------------------
That model developed by facebook and that is our first model we implemented on pyfbad.

   >>> train_model(self, df_model)
Train a Prophet model with given dataframe

   >>> train_forecast(self, forecast, bound_coefficient)
Tries to predict anomalies based on training results. 
**bound_coefficient (float):** optimization coefficient for anomaly number


.. autosummary::
   :toctree: generated

   PYFBAD
