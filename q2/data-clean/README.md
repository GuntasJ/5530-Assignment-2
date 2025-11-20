The cleaned dataset differs from the original dataset in the following ways:

Analysis had to be done on glucose, blood pressure, and BMI so these were preprocessed and cleaned

All 0 values of glucose and BMI resulted in listwise deletion, aka, deletion of the row. This is as they were in small enough percentages (<1%). Also, the correlation of missing values
between glucose and BMI were very similar, such that deleting these rows is not likely to spill over into other rows.

Blood pressure values were imputated with the mean of the blood pressure. This was done as deleting all blood pressures would have been too many instances deleted.
