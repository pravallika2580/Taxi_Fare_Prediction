# Taxi_Fare_Prediction
This repository contains data for predicting taxi fares , including information on taxi rides, passenger counts, distances, and fare amounts. The dataset is split into training, test, and sample files.
Dataset Files

**1.train.csv** - Contains the main data for training the model.
* **Entries:** 175,000
* **Columns:** 17
* **Features:**

  
    VendorID, tpep_pickup_datetime, tpep_dropoff_datetime, passenger_count, trip_distance, RatecodeID, store_and_fwd_flag, PULocationID, DOLocationID, payment_type, extra, tip_amount, tolls_amount, improvement_surcharge, total_amount, congestion_surcharge, Airport_fee
  
**2.test.csv** - Used for evaluating the model's predictions.

* **Entries:** 50,000
* **Columns:** 16
* **Features:** Same as train.csv except for total_amount

**3.sample.csv** - Provides sample predictions for the test dataset.

* **Entries:** 1,000
* **Columns:** 2
* **Features:** ID, total_amount

  # Data Details
* **VendorID:** ID of the taxi company.
* **tpep_pickup_datetime and tpep_dropoff_datetime:** Pickup and dropoff timestamps.
* **passenger_count:** Number of passengers on the ride.
* **trip_distance:** Distance of the trip in miles.
* **RatecodeID:** Rate category for the ride.
* **store_and_fwd_flag:** Whether the data was stored or forwarded.
* **PULocationID and DOLocationID:** Pickup and dropoff location codes.
* **payment_type:** Payment type used.
* **tip_amount:** Tip amount added by the customer.
* **tolls_amount:** Any toll fees.
* **improvement_surcharge:** Additional surcharge for service improvement.
* **congestion_surcharge:** Surcharge due to congestion.
* **Airport_fee:** Additional fee for airport pickups.

# Usage
This dataset can be used for training machine learning models to predict taxi fares based on ride and passenger data. Models may use features such as distance, location, and time information to estimate the fare.
