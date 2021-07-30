# dsci100-002-group9-project

# Evaluation of K-Nearest Neighbours Prediction on Algerian Forest Fire based on Fine Fuel Moisture Code (FFMC) and Drought Code (DC)

While forest fires can be incredibly destructive to the environment, they are also a natural part of forest life cycles. To mitigate risks and better prepare local areas, being able to predict if a forest fire will occur at a given time would be very beneficial. 

Researchers have collected data on forest fires in two regions of Algeria, Bejaia and Sidi Bel-Abbes, from June 2012 to September 2012 (https://archive.ics.uci.edu/ml/datasets/Algerian+Forest+Fires+Dataset++). This dataset includes 244 total observations and 10 variables: 
- Temperature, in Celsius degrees
- Relative humidity, in %
- Wind speed, in km/h
- Rain, in mm
- Fine Fuel Moisture Code (FFMC)
- Duff Moisture Code (DMC)
- Drought Code (DC)
- Initial Spread Index (ISI)
- Buildup Index (BUI)
- Fire Weather Index (FWI)

Six of these variables (FFMC, DMC, DC, ISI, BUI and FWI) are components of the Forest Fire Weather Index System (https://cwfis.cfs.nrcan.gc.ca/background/summary/fwi), indicating relative potential for wildfires, and are calculated from the remaining four variables (temperature, relative humidity, wind speed and rain).

<img src='https://cwfis.cfs.nrcan.gc.ca/images/fwi_structure.gif' width='400'>

Source: https://cwfis.cfs.nrcan.gc.ca/images/fwi_structure.gif

Using this dataset, we will attempt to perform K-nearest neighbours classification to predict from a new set of measurements if a forest fire will occur, and we will evaluate the accuracy of such predictions.
