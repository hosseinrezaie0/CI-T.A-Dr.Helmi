# House Price Prediction Dataset.
The dataset contains 2000 rows of house-related data, representing various features that could influence house prices.
Below, we discuss key aspects of the dataset, which include its structure, the choice of features, and potential use cases for analysis.

## 1. Dataset Features
The dataset is designed to capture essential attributes for predicting house prices, including:
Area: Square footage of the house, which is generally one of the most important predictors of price.
Bedrooms & Bathrooms: The number of rooms in a house significantly affects its value. Homes with more rooms tend to be priced higher.
Floors: The number of floors in a house could indicate a larger, more luxurious home, potentially raising its price.
Year Built: The age of the house can affect its condition and value. Newly built houses are generally more expensive than older ones.
Location: Houses in desirable locations such as downtown or urban areas tend to be priced higher than those in suburban or rural areas.
Condition: The current condition of the house is critical, as well-maintained houses (in 'Excellent' or 'Good' condition) will attract higher prices compared to houses in 'Fair' or 'Poor' condition.
Garage: Availability of a garage can increase the price due to added convenience and space.
Price: The target variable, representing the sale price of the house, used to train machine learning models to predict house prices based on the other features.

## 2. Feature Distributions
Area Distribution: The area of the houses in the dataset ranges from 500 to 5000 square feet, which allows analysis across different types of homes, from smaller apartments to larger luxury houses.
Bedrooms and Bathrooms: The number of bedrooms varies from 1 to 5, and bathrooms from 1 to 4. This variance enables analysis of homes with different sizes and layouts.
Floors: Houses in the dataset have between 1 and 3 floors. This feature could be useful for identifying the influence of multi-level homes on house prices.
Year Built: The dataset contains houses built from 1900 to 2023, giving a wide range of house ages to analyze the effects of new vs. older construction.
Location: There is a mix of urban, suburban, downtown, and rural locations. Urban and downtown homes may command higher prices due to proximity to amenities.
Condition: Houses are labeled as 'Excellent', 'Good', 'Fair', or 'Poor'. This feature helps model the price differences based on the current state of the house.
Price Distribution: Prices range between $50,000 and $1,000,000, offering a broad spectrum of property values. This range makes the dataset appropriate for predicting a wide variety of housing prices, from affordable homes to luxury properties.

LINK: https://www.kaggle.com/datasets/zafarali27/house-price-prediction-dataset
