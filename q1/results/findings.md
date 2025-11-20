There were no specific findings that were supposed to be done as per the assignment instructions. For my findings, I have decided to include some of my thought processes 
since that is the reason for which this excersise was done for. 

<img width="1532" height="1034" alt="image" src="https://github.com/user-attachments/assets/35247db7-e30b-4540-9978-9a14c3b9cef2" />
This image shows that missing values in power, seat, and engine are correlated, and so they can be removed together. 

New_Price has 86% missing, so this column should be dropped


| Feature Name | Value |
| ------------ | ------|
| Name |	0.000000 |
| Location | 0.000000 |
| Year |	0.000000 |
| Kilometers_Driven |	0.000000 |
| Fuel_Type |	0.000000 |
| T ransmission |	0.000000 |
| Owner_Type | 0.000000 |
| Engine |	0.000000 |
| Power |	0.000000 |
| Seats |	0.000000 |
| Price |	0.000000 | 
| mileage_by_liter |	0.086073 |
| mileage_by_kg |	99.948356 |

From here, it can be seen that mileage_by_kg has too many missing instances, and thus, it should be deleted
