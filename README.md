# Console-finances

This project required a few calculations to be done using a 2D array as an input value that would return the total number of months, the total amount in profit, the average change, and the greatest increase and decrease in profits and losses.
Each aspect of the operation is represented by a function.

-transformData: This takes in a 2D array and returns an array of objects that are easier to work with
-totalProfits: This will take in an array of objects that has the properties month and amount and calculate the total in a loop
-averageChange: This will take the transformed data and return an array of the month to month changes in amounts
-highestChange: This will use the data returned by average change to determine the greatest increase/decrease in profit/losses and return the values in an object
-display: This gathers the results of all the calculations just outlined and creates the text to be displayed on the console
-render: This is used to generate the html that will be displayed on the page and styled with css
