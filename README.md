# Power-Outage-Prediction
Predicting power outages using extreme weather events

This project is structured as follows.
- `codes` contains the python notebooks for data preprocessing, exploratory data analysis, and modeling.
   - `codes/preprocessing` contains the python notebook `merge.ipynb,` where we read power and weather data and merge them together into one dataset, indicating whether a weather event yielded a power outage.
   - `codes/eda` contains python notebooks for exploratory data analysis, one for each type of weather.
   - `codes/modeling` contains python notebooks for training models and evaluating their performance. For each weather type of interest, there is one notebook including brief, organized code illustrating how we train models for the given type of weather. Additionally, there are subdirectories for each weather type, containing the more detailed used during our experiments.
   - `codes/results` contains python notebooks describing the results of our trained models.
   - `codes/misc_old` contains miscellaneous/old code not used in the final version of our project (kept for posterity).
- `merged` contains the merged datasets outputted by `merge.ipynb`
- `power_data` contains the datasets for power outages.
- `models` contains the saved, trained models.
- `misc_old` contains miscellaneous/old files not used in the final version of our project (kept for posterity).
