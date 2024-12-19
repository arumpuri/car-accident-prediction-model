# car-accident-prediction-model

This repository contains a machine learning model designed to predict car accidents based on various factors such as weather conditions, road type, time of day, and driver-related features. The model aims to enhance road safety by identifying patterns and potential risks associated with different driving conditions.

# Features

## 1. Weather

The impact of weather conditions on the likelihood of accidents:

- Clear: No adverse weather conditions.

- Rainy: Rainy conditions increase the chance of accidents.

- Foggy: Foggy conditions reduce visibility, increasing accident chances.

Snowy: Snow can cause slippery roads and higher accident probability.

- Stormy: Stormy weather can create hazardous driving conditions.

## 2. Road Type

The type of road influences the probability of accidents:

- Highway: High-speed roads with higher chances of severe accidents.

- City Road: Roads within city limits, typically with more traffic and lower speeds.

- Rural Road: Roads outside urban areas, often with fewer vehicles and lower speeds.

- Mountain Road: Roads with curves and elevation changes, increasing accident risk.

## 3. Time of Day

The time of day when the accident occurs:

- Morning: The period between sunrise and noon.

- Afternoon: The period between noon and evening.

- Evening: The period just before sunset.

- Night: The nighttime, often associated with reduced visibility and higher risk.

## 4. Traffic Density

The level of traffic on the road:

- 0: Low density (few vehicles).

- 1: Moderate density.

- 2: High density (many vehicles).

## 5. Speed Limit

The maximum allowed speed on the road.

## 6. Number of Vehicles

The number of vehicles involved in the accident, ranging from 1 to 5.

## 7. Driver Alcohol

Whether the driver consumed alcohol:

- 0: No alcohol consumption.

- 1: Alcohol consumption (which increases the likelihood of an accident).

## 8. Accident Severity

The severity of the accident:

- Low: Minor accident.

- Moderate: Moderate accident with some damage or injuries.

- High: Severe accident with significant damage or injuries.

## 9. Road Condition

The condition of the road surface:

- Dry: Dry roads with minimal risk.

- Wet: Wet roads due to rain, increasing the risk of accidents.

- Icy: Ice on the road, significantly increasing the risk of accidents.

- Under Construction: Roads under construction, which may have obstacles or poor road quality.

## 10. Vehicle Type

The type of vehicle involved in the accident:

- Car: A regular passenger car.

- Truck: A large vehicle used for transporting goods.

- Motorcycle: A two-wheeled motor vehicle.

- Bus: A large vehicle used for public transportation.

## 11. Driver Age

The age of the driver. Values range from 18 to 70 years old.

## 12. Driver Experience

The years of experience the driver has. Values range from 0 to 50 years of experience.

## 13. Road Light Condition

The lighting conditions on the road:

- Daylight: Daytime, when visibility is typically good.

- Artificial Light: Road is illuminated with streetlights.

- No Light: Road is not illuminated, typically during the night in poorly lit areas

# Libraries Used

This project requires the following Python libraries:

- Python: The core programming language used for this project.

- Pandas: For data manipulation and analysis.

- NumPy: For numerical computations.

- scikit-learn (sklearn): For machine learning model building and evaluation.

- Matplotlib: For data visualization.

- Seaborn: For advanced data visualization and statistical graphics.

Ensure these libraries are installed before running the project.

# Usage

- Clone this repository:

  
```

git clone https://github.com/yourusername/car-accident-prediction-model.git

```

- Install the dependencies

- Run the model pipeline or explore the notebooks for analysis (I executed this code on Kaggle. Please ensure you update the dataset path accordingly before running it in your environment.)

# License

This project is licensed under the MIT License. See the LICENSE file for more details.

# Contributions

Contributions are welcome! Please open an issue or submit a pull request with any improvements or suggestions.
