# 🚗 Car Price Prediction
Congratulations! You’ve completed the simulator course. Now it’s time to test your knowledge and tackle a new machine learning task — independently.
Once you finish, submit your work for review: the reviewer will send feedback within 24 hours. After that, you’ll need to revise the project and go through another round of review.
You’ll likely need to refine the case several times based on comments — that’s perfectly normal.
The project is considered complete once the reviewer approves all revisions.

## 📘 Project Description
The used car sales service “No Accidents, No Paint Jobs” is developing an app to attract new customers. The app will allow users to estimate the market value of their car.
Build a model that can accurately predict car prices. You’ll have access to data on technical specifications, configurations, and prices of other vehicles.
Key criteria for the client:

- Prediction quality
- Model training time
- Model prediction time

## 🛠️ Project Instructions
To strengthen your analysis, don’t limit yourself to gradient boosting. Try simpler models — sometimes they perform better. These rare cases are easy to miss if you always default to boosting.
Experiment and compare model characteristics: training time, prediction time, and accuracy.
Main steps:

1. Load the data from /datasets/autos.csv.
2. Explore the data. Fill in missing values and handle anomalies in the columns. Remove any non-informative features.
3. Prepare training and testing datasets.
4. Train different models — one must be LightGBM, and at least one must not be a boosting model. Try different hyperparameters for each.
5. Analyze training time, prediction time, and model quality.
6. Based on the client’s criteria, select the best model and evaluate its performance on the test set.

## 🧮 Notes
- Use the RMSE metric to evaluate model quality.

- RMSE should be less than 2500.

- Learn the LightGBM library and use it to build gradient boosting models.

- You can measure Jupyter Notebook cell execution time using a special command — look it up.

- Gradient boosting models may take a long time to train, so only tweak 2–3 parameters.

- If Jupyter Notebook crashes, delete unnecessary variables using:
```python
del features_train
```

## 📂 Data Description
The dataset is located in /datasets/autos.csv.

Features:
- DateCrawled — date the listing was scraped from the database
- VehicleType — type of car body
- RegistrationYear — year of registration
- Gearbox — transmission type
- Power — horsepower
- Model — car model
- Kilometer — mileage (km)
- FuelType — fuel type
- Brand — car brand
- Repaired — whether the car has been repaired
- DateCreated — date the listing was created
- NumberOfPictures — number of car photos
- PostalCode — user’s postal code
- LastSeen — date of last user activity

Target:
- Price — price in euros

## ✅ How Will My Project Be Evaluated?
We’ve prepared project evaluation criteria that reviewers follow. Before starting, study them carefully.
Reviewers will check:
- Are all steps from the instructions completed?
- How do you prepare the data?
- What models and hyperparameters do you explore?
- Do you avoid code duplication?
- What conclusions do you draw?
- Is the project well-structured?
- Is the code clean and organized?

Everything you need is in the cheat sheets and notes from previous topics.

Good luck!
