# CSE4820_Final_Project

USE FLIGHT_DATA_ERA5

ALSO NORMALIZE DATA

Demo (Kyle) will make interactive thing where you type in flight departure and basic weather data, will give prob. Will do it on majority vote.

For Models start with these features:

significant_features = [
    "VC_windspeed",
    "VC_cloudcover",
    "VC_visibility",
    "VC_temp",
    "VC_humidity",
    "VC_precip",
    "VC_2h_temp",
    "VC_2h_humidity",
    "VC_2h_precip",
    "VC_2h_windspeed",
    "VC_2h_visibility",
    "Market Share",
    "Passenger Load Factor",
    "OTP Index",
    "Hourly_Airport_Departures",
    "Distance",
    "Airport_Congestion_Index"
]

TODO: 
- Rerun models, extensively search for best features (can do foward selection)
- Compare results
- Help others (Kyle)
- Random Forest Binary (Kyle)
- Unsupervised clustering (Kyle + Addie)
- Run NN for multi-class (Cristian)
- Turn models into Ordinal Classification Models (Cristian)
- Feature Importance (ALL)
- Learning Curves (ALL)

MODELS (both):
- KNN
- Linear
- NN
- CNN (can use my model code)
-Forest
  
note for multiclass try smote if interested 


  At end of both, run majority. We have 5 Binary Models MODEL ESEMBLES

MODELS (binary only):
- logistic

Can do unsupervised if time.
