# Power-Outage-Prediction
Predicting power outages using extreme weather events

This project is structured as follows.
- `codes` contains the python notebooks for data preprocessing, exploratory data analysis, and modeling.
   - `codes/preprocessing` contains the python notebook `merge.ipynb,` where we read power and weather data and merge them together into one dataset, indicating whether a weather event yielded a power outage.
   - `codes/eda` contains python notebooks for exploratory data analysis, one for each type of weather.
   - `codes/modeling` contains python notebooks for training models and evaluating their performance. There is one notebook for each type of weather event that we run models on (namely, tornados, lightning, and mesocyclones).
- `merged` contains the merged datasets outputted by `merge.ipynb`
- `power_data` contains the datasets for power outages.
- `models` contains the saved, trained models. 
