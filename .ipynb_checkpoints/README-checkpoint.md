# House-Rent-Prediction
The rent of a house depends on a lot of factors. With appropriate data and Machine Learning techniques, many real estate platforms find the housing options according to the customer’s budget. 

To build a house rent prediction system, we need data based on the factors affecting the rent of a housing property. I found a dataset from Kaggle which includes all the features we need. You can download the dataset from [here](https://www.kaggle.com/datasets/iamsouravbanerjee/house-rent-prediction-dataset).
## Dataset Columns
- BHK: Number of Bedrooms, Hall, Kitchen.
- Rent: Rent of the Houses/Apartments/Flats.
- Size: Size of the Houses/Apartments/Flats in Square Feet.
- Floor: Houses/Apartments/Flats situated in which Floor and Total Number of Floors (Example: Ground out of 2, 3 out of 5, etc.)
- Area Type: Size of the Houses/Apartments/Flats calculated on either Super Area or Carpet Area or Build Area.
- Area Locality: Locality of the Houses/Apartments/Flats.
- City: City where the Houses/Apartments/Flats are Located.
- Furnishing Status: Furnishing Status of the Houses/Apartments/Flats, either it is Furnished or Semi-Furnished or Unfurnished.
- Tenant Preferred: Type of Tenant Preferred by the Owner or Agent.
- Bathroom: Number of Bathrooms.

## Prediction Example
Enter House Details to Predict Rent
Number of BHK(1-6):  1
Size of the House(10-8000):  1000
Area Type (Super Area = 1, Carpet Area = 2, Built Area = 3):  3
Mumbai:4000
Chennai:6000
Bangalore:5600
Hyderabad: 5000
Delhi:1100
Kolkata:7000
Pin Code of the City:  7000
Furnishing Status of the House (Unfurnished = 0, Semi-Furnished = 1, Furnished = 2):  0
Tenant Type (Bachelors = 1, Bachelors/Family = 2, Only Family = 3):  2
Number of bathrooms(1-10):  1
1/1 ━━━━━━━━━━━━━━━━━━━━ 0s 29ms/step
Predicted House Price =  [[22519.922]]