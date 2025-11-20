<img width="540" height="374" alt="image" src="https://github.com/user-attachments/assets/ee3133b3-5f8b-4c47-85c5-1ac166004954" />
<img width="540" height="374" alt="image" src="https://github.com/user-attachments/assets/5a1a0dff-160d-46fa-9fb5-ef9e0400994b" />

I found that when analzying the sample mean and max glucose values compared to the population mean and max values, the mean values are similar.
This is to be expected as a sample of 25, when average out, can flatten the outliers or more extreme values that may be included. However, there does exist
significant difference in the max glucose levels, about 15 points so. This is expected as the max value does not have a way to flatten its results like mean does. This makes it
sensitive to the small sample size chosen. 

<img width="531" height="374" alt="image" src="https://github.com/user-attachments/assets/89c09b0c-1fd6-478f-aa42-00c1c430537b" />

Here, I found that the sample BMI was around 3-4 points higher than the population BMI. This is not particulary significant, and it likely as a result of the sample size picking up some 
higher values. The 98 percentile helps find the more extreme values, which is probably what resulted here. 

<img width="531" height="374" alt="image" src="https://github.com/user-attachments/assets/deaa701c-a6d0-4053-8869-e15b8e73bee0" />
<img width="531" height="374" alt="image" src="https://github.com/user-attachments/assets/8872dc74-0250-4fe9-94e6-64c7170f1495" />
<img width="540" height="374" alt="image" src="https://github.com/user-attachments/assets/796490fa-13a4-457b-84cc-6eb5ae4da187" />

When looking at the bootstrap results, I found that the average bootstrap results for mean, std, and 98 percentile for blood pressure were almost the same as the population results.
This is to be expected, as with 500 samples, and 150 occurences in each, there exists enough variation for extreme values to be captured and treated. The final averaging out flattens
these values, which results in the bootstrap and population results being almost the same. 
