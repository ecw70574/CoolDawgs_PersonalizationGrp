# ----- SIMULATED FEATURES DESCRIPTION ----- 

### There are 39 features in the simulated dataset (*FullSimDF.csv*). They can be categorized as internal or external attributes, and as numerical, categorical, or boolean variables. This dataset will be used to train the model, as the number of actual dogs available for data collection is limited.

### Below are the features and their definitions for clarity. More details and visualizations are found in the *EDA on Simulated Data* notebook.


* **Breed** - specific breed of dog 

* **Age** - how old the dog is (in years)

* **Weight** - dog's weight (in kg)

* **Gender** - male or female

* **Color** - color of the dog's fur (impacts how much heat they absorb)

* **Coat Length** - how long the fur is (short, medium, or long)

* **Coat Type** - texture/style of the fur (smooth, silky, wavy, etc.)

* **Energy Level** - how active the dog is currently (3.0 to 5.0 scale)

* **Playfulness Level** - how much the dog wants to interact or play (3.0 to 5.0 scale)

* **is_brachycephalic** - yes/no flag for flat-faced and condensed snout breeds (like pugs) who struggle to pant and cool down 

* **size_category** - general size of dog (toy, medium, large, etc.)

* **Spayed/Neutered** - whether the dog has had surgery to prevent breeding 

* **Indoor/Outdoor** - where the dog is located at the moment

* **Season** - what time of the year it is (spring, summer, fall, winter)

* **Sun Exposure** - how much direct sunlight is hitting the dog (0.0 to 6.0 scale)

* **Wind Cooling Effect** - how much the wind (°C) is helping to cool the dog's body 

* **Station_Temp** - temperature (°C) from the nearest official weather station 

* **Station_Humidity** - humidity (% as decimal) from the nearest official weather station

* **Ambient_Temp** - actual temperature (°C) in the dog's immediate area

* **Ambient_Humidity** - actual humidity (% as decimal) in the dog's immediate area

* **T_Device** - temperature (°C) recorded by the wearable sensor on the dog's collar

* **H_Device** - humidity (% as decimal) recorded by the wearable sensor on the dog's collar

* **breed_wt_mu** - average weight (in kg) for the specific breed

* **breed_wt_sd** - how much weight (in kg) usually varies within the specific breed

* **ideal_weight** - calculated "healthy" weight the dog should be (in kg)

* **pct_of_ideal** - ratio (% as decimal) of the dog's current weight compared to its ideal 

* **BCS_cont** - body condition score (how much fat a dog has compared to its muscles and bones)

* **BCS** - body condition score rounded to a whole number (1 is underweight, 9 is overweight)

* **Temp_Diff** - difference between sensor temperature and actual temperature

* **Hum_Diff** - difference between sensor humidity and actual humidity

* **CBT_simulated** - core body temperature (simulated dog's internal heat - most important feature!)

* **is_old** - yes/no flag if the dog has reached senior age for its specific breed

* **is_overweight** - yes/no flag if the dog's weight is significantly above its ideal

* **heat_stress_risk** - flag indicating if the current conditions put the dog in danger

* **High_humidity_fordogs** - yes/no flag for humidity levels that make panting difficult

* **prior_heat_related_injury_est** - estimate of whether the dog has overheated in the past

* **simulated_heat_injury_flag** - flag showing if a simulated heat injury occurred currently

* **target2Category** - flag identifying if the dog is safe or at risk 

* **target3Category** - state of risk in the dog (normal, heat stress, heat stroke)