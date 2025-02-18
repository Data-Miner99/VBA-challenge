# Module 2 Challenge VBA-challenge

You are well on your way to becoming a programmer and Excel expert! In this homework assignment, you will use VBA scripting to analyze generated stock market data.

# Before You Begin

1. Create a new repository for this project called VBA-challenge. Do not add this assignment to an existing repository.
2. Inside the new repository that you just created, add any VBA files that you use for this assignment. These will be the main scripts to run for each analysis.

# Instructions
1. Create a script that loops through all the stocks for each quarter and outputs the following information:
   * The ticker symbol
   * Quarterly change from the opening price at the beginning of a given quarter to the closing price at the end of that quarter.
   * The percentage change from the opening price at the beginning of a given quarter to the closing price at the end of that quarter.
   * The total stock volume of the stock. The result should match the following image:
   
![image](https://github.com/Data-Miner99/VBA-challenge/assets/101415559/615032fc-d5af-4c23-bbba-09b0ba54edf6)

2. Add functionality to your script to return the stock with the
   * "Greatest % increase",
   * "Greatest % decrease", and
   * "Greatest total volume".
The  solution should match the following image:

![image](https://github.com/Data-Miner99/VBA-challenge/assets/101415559/6e59b505-a06a-4387-beb9-57ac2224a85f)

3. Make the appropriate adjustments to your VBA script to enable it to run on every worksheet (that is, every quarter) at once.

NOTE:
Make sure to use conditional formatting that will highlight positive change in green and negative change in red.

# Other Considerations
1. Use the sheet alphabetical_testing.xlsx while developing your code. This dataset is smaller and will allow you to test faster. Your code should run on this file in just a few seconds.
2. Make sure that the script acts the same on every sheet. 

# References
Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
