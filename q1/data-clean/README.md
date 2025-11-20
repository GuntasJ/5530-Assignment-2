The cleaned data differs from the original data in the following ways:

All null or missing values have been removed. This includes the mileage_by_kg and New_Price columns

Missing values of power, engine, and seats were removed as they were small and number, and almost all of these missing values were missing all together at the same time in the same row

Engine no longer has its cc suffix

Power no longer has its bhp suffix 

Mileage has been replaced with mileage_by_liter, which encompasses all "kmpl" suffix ending instances found in Mileage. The remaining missing milsage_by_liter were imputed with the mean.

Fuel_Type has had one-hot encoding applied to it, producing Fuel_Type_Diesel, Fuel_Type_Electric, and Fuel_Type_Petrol. These values are now either 1 or 0

Transmission has had one-hot encoding applied to it, producing Transmission_Automatic and Transmission_Manual. These values are now either 1 or 0

Age has been renamed to Age_Years, signifying that it is measured in years.

Age_Months was created which is the age of the car in months
