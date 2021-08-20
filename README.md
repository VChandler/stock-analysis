# Module 2 Challenge
## Overview of Project
For this project, there were two objectives:
* Examine the volume and returns for a number of stocks across multiple years
* Examine whether refactoring code resulted in more efficient execution of the VBA program

## Results
### Stock Comparison
Regarding the stocks themselves, 2017 saw broad success of the stocks.

![2017_returns](https://user-images.githubusercontent.com/88070999/130162775-11dc6761-b280-42c7-85f8-8376978108a4.png) 

Most increased in terms of a yearly return.

In 2018 however, the selected stocks nearly add showed a loss for the year. 

![2018_returns](https://user-images.githubusercontent.com/88070999/130162795-11f0879c-df89-48d9-8084-e4bb83dfd556.PNG) 

Though two of the higher volume stocks had a positive return, the stock with the 2nd highest total volume (SPWR) dropped by 44.6%.

In terms of the recommendation to the client, stocks ENPH and RUN are the only two stocks that had positive returns for both years.

### Refactoring
Regarding refactoring, the time required to run the program decreased by nearly 1 second for both years, indicating much more efficient code than the earlier version of the exercise.

## Summary
### Refactoring in General
Generally speaking, a big advantage of refactoring code is to attempt to make it more efficient.  If successful, vast improvements are possible in the processing time required for the program.  However, there can be significant disadvantages as well.  For one, the time required to revisit code and find opportunities to improve it may take a significant amount of time.  Also, there is no guarantee that changes will have an impact on the time required.  It is possible that the time required to refactor the code may far outweigh any incremental benefits gained.

### Refactoring of Challenge
For the assignment, the use of arrays was able to capture the values for ALL the stock tickers by only iterating through the source data one time.  Without using the arrays (and nested loops), the code would have had to cycle through the source data completely for each stock ticker.  Further, the more efficient code may have resulted in better use of the computer's memory- not too critical for this particular program, but could potentially be helpful for much larger programs.

As a result of the changes, about 1 second was shaved off the processing time required.  However, the amount of time needed to refactor the code (from the previous version used in the assignment) was significant.  For this smaller dataset and the small amount of time improvement realized, refactoring the code may have been counterproductive.
