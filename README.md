# CSE4820_Final_Project

USE FLIGHT_DATA_ERA5

ALSO NORMALIZE DATA

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
- Shallow NN
- CNN (can use my model code)
- Maybe try to do average thing said in class where all 3 models run and majority picks decision

  ASSESS with SoftMax, rewards us for being confidently right.

MODELS (binary only):
- logistic

Can do unsupervised if time.
