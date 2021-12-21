# Stock Analysis

## Overview of the Project

### Purpose
The purpose of this stock analyis project was to give Steve the ability to analyze the entire data set for 2017 and 2018 with just the click of a button. By writing VBA script we were able to refactor our original code to be faster and more efficient. The code allowed us to conditionally format our results to show which stocks had a positive return (green) and which ones had a negative return for the year (red). This allows Steve's parents to see which stocks they could invest in and how they performed compared to one another and if they should make some changes to their current portfolio. 

## Results
By running our code, we can see by the screenshots below that 2017 was a far more successful year for the returns than 2018 was.

![2017 Returns](https://user-images.githubusercontent.com/90940985/146962271-1e3e874a-40be-4ade-ab83-5dbb504a298c.jpg)
![2018 Stock Returns](https://user-images.githubusercontent.com/90940985/146962289-4b6ab404-d8de-4641-a27c-476caccc50a2.jpg)

Almost every stock in 2017 saw growth other than TERP, compared to 2018 where only 2 out of the 12 companies saw growth. The returns on these stocks are very volatile and could prove to be risky investments. Some stocks were  up over 100% in 2017, but down over 60% in 2018. The high reward in 2017 comes with the high risk shown by the results in 2018. The original run times of our code are shown below and are just over half a second long. 
![2017 Run Time Original](https://user-images.githubusercontent.com/90940985/146962317-f5464696-6eb0-45bc-a3f9-a3c618d2491e.jpg)
![2018 Run Time Original](https://user-images.githubusercontent.com/90940985/146962328-c1f585d0-ad08-416e-a666-69fedb0525d4.jpg)

When I refactored the code to be more effecient, the run time for both 2017 and 2018 decreased significantly compared to the original. 
![2017 Run Time](https://user-images.githubusercontent.com/90940985/146962367-980a8994-316e-4279-992d-9780f5b60b79.jpg)
![2018 Run Time](https://user-images.githubusercontent.com/90940985/146962378-9bb33cb2-9a3f-4c55-9e37-48d4613cae5c.jpg)

## Summary

### What are the advantages or disadvantages of Refactoring code?
The advantages to refactoring code are that it makes the code more efficient and can cut down on run times as we saw from this project. It can also make the code cleaner and easier to read for future changes or for other users trying to execute/edit the code. Some disadvantages are that it can be time consuming or you may not be able to properly refactor it to where it works with its intended purpose.

### How do these pros and cons apply to refactoring the original VBA script?
By looking at the run times of both the original code and refactored code, it is clear that the refactored code fulfilled its purpose of being faster than the original. Refactoring was definitely time consuming, the original code was completed and running correctly for me and refactoring it took an extra few hours to work out all the issues and debug the code just to have a slight difference in run time.
