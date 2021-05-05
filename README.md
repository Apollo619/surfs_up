# Surfs Up

## Overview Analysis
I want to start a business in Hawaii called *”Surf n’ Shake”*. A shop that serves surf boards and ice cream to tourist and locals. The investor I approached, loves the idea, but is worried about the weather and wants me to analyze weather data before presenting to his board. 

### Purpose:
A previous venture fell through due to bad weather so W. Avy asks us to perform analytics on weather data collected from the island of Oahu. Jupyter notebook was used to code the analysis and SQLite used to store the results into a database. See below image for script.
![]( https://github.com/Apollo619/surfs_up/blob/main/Resources/JN%20code.PNG)

## Results:
-	Using the script shown above, two tables of statistics were generated for the months of June and December based on the temperatures collected (see below images for results). Referencing the tables, you can see that the month of June is on average 3.9 degrees warmer than the month of December. 
![]( https://github.com/Apollo619/surfs_up/blob/main/Resources/june%20temps%20mean.PNG) ![]( https://github.com/Apollo619/surfs_up/blob/main/Resources/december%20temps%20mean.PNG)

-	June and December were chosen as they should exhibit the greatest variation in temps. The average temps would indicate that this is not the case, but when looking at the images below, the differences between maximum and minimum temperatures indicate a greater variance for December (27 degrees) versus June (21 degrees), and this variation can cause unpredictable financial forecasting. 
![]( https://github.com/Apollo619/surfs_up/blob/main/Resources/june%20temps%20maxmin.PNG) ![]( https://github.com/Apollo619/surfs_up/blob/main/Resources/december%20temps%20maxmin.PNG)

-	One thing, I believe, that is a key difference in the weather between June and December is the number of data points collected and analyzed. As you can see from the images below, the total count for June is approximately 183 more data points than December. The difference in data point collected could potentially shrink or widen the deviation for all statistical results.  
![]( https://github.com/Apollo619/surfs_up/blob/main/Resources/june%20count.PNG) ![]( https://github.com/Apollo619/surfs_up/blob/main/Resources/december%20counts.PNG)

## Summary:
If analyzing temperature was the only key component to opening a surf board and ice cream shop called *”Surf n’ Shake”*, based on the results for the island of Oahu in Hawaii this would be an ideal location. When looking at the temps for June and December, which was determined to represent the greatest fluctuation for weather, you can predict with a high level of confidence that the demand for ice cream and surfing would be consistent year-round.
Unfortunately, temperature isn’t the only variable that needs to be considered when determining the weather. **Precipitation** is another key factor that needs to be analyzed as rain can cause inactivity for ice cream and surfing for locals and tourist alike. An additional query is needed to perform statistical analysis for precipitation to help get a better understanding of the weather for Oahu. See the below images of precipitations for June and December rain.
![]( https://github.com/Apollo619/surfs_up/blob/main/Resources/june%20precipitation.PNG) ![]( https://github.com/Apollo619/surfs_up/blob/main/Resources/december%20precipitation.PNG) 
As you can see from the above images, precipitation on average is low for both months but an outlier that needs to be evaluated is that the means for both June and December are closer the 75% quartile versus the 50% quartile, which indicated the data is left skewed based on the max precipitation recorded in both months. This can bring down the overall accuracy of predictive success models due to the outlier in rains. 
