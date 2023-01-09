# Pseudocode for c4 challenge financial analysis
- Create github Repo //
- Clone repo to computer //

## Do layout
- Console log Financial analysis //


## total no of months included in dataset
- Create variable for the total number of months (SumMonths) //
- Calc total no of months from finances array and variable.length //
- Commit and comment reminder //

## net sum of profit/loss combined
- Create total profit/loss (sumPL) variable //
- Create a for loop that calcs sum of [i][1] of finances variable //
- Add console.log displaying //
- Commit and comment reminder//


## Average of the changes in profit/loss over period
- Create profit/loss average (AvgChgPL) variable
- Create for loop on Finances array that targets [1] of each element and finds the difference between its previous data point (i = 0, i < v.length, i++) and inputs into new variable (OR array?)
- Add total to 
- - potentially make new array from finances array.
- Do avg calc for new array and input to new variable (AvgChgPL)
- Add up each months change/difference, combine then divide by total months.

- Add console.log displaying
- Commit and comment reminder

<!-- NEXT TWO POTENTIALLY PART OF ABOVE POINT -->

## Total change in profit month to month
- Add console.log displaying
- Commit and comment reminder

## average changes in profit month to month.
- Add console.log displaying
- Commit and comment reminder

<!--  -->

## Greatest increase in profits (date and amount) over period
- Create greatest inc in profits variable (GIncP)
- Create a for loop that calcs which [x] of [i][1] of finances variable that was + had the most change
- input into GIncP variable
- Add console.log displaying
- Commit and comment reminder

## Greatest decrease in losses (date and amount) over period
- Create greatest dec in losses variable (GDecL)
- Create a for loop that calcs which [x] of [i][1] of finances variable that was - had the most change
- input into GDecL variable
- Add console.log displaying
- Commit and comment reminder

## Cleaning up
- clean/remove console.log
- Commit and comment reminder
