# What drives the price of a car?

Click [here](https://github.com/hjag038/used_car_price/blob/main/used_car_price.ipynb) to access the Jupyter Notebook.

## Used Car Pricing Insights Report:

### Objective

Help your dealership understand what vehicle characteristics most influence used car prices so you can refine inventory choices, set smarter prices, and highlight features buyers care about.

### Key Takeaway

Newer Cars and Lower Mileage = Higher Value

Across the full dataset of 426,000 vehicles, the strongest and most consistent predictors of higher price are:

- Newer model years

* Lower odometer readings

These two variables explain more price variation than any other features.

### Action: 

Prioritize newer vehicles and those with mileage well below average for their year.

### Modeling Results (What We Learned About Prediction)

The statistical models (Linear Regression, Polynomial Regression, Ridge, and Lasso) showed very high error rates, meaning they cannot accurately predict exact prices. This is expected because real-world used car prices depend on factors not captured in the dataset, such as:

1. Trim level & features

2. Accident and service history

3. Interior/exterior quality

4. Regional pricing trends

5. Dealer negotiation practices

Even though price prediction is imprecise, the models still clearly identify the direction and strength of key price drivers.

### What This Means for Your Dealership

1. Improve acquisition decisions

Focus on vehicles that hold value:

- Newer

* Lower mileage

+ Strong manufacturers

2. Highlight top selling points in ads and online listings, emphasize:

- Model year

* Mileage

+ Condition

3. Use insights, not exact predictions

The goal isn’t to predict a perfect price—it’s to understand what buyers value and adjust your inventory and pricing strategy accordingly.

### Next Steps:

To make future predictions more accurate, adding more detailed vehicle information would be helpful (trim, accident history, features - leather seats, sunroof etc.). With richer data, more advanced models could provide stronger pricing guidance.
