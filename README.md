# Structural-Testing

In this project I have applied three white box techniques on the ATM system.

The focal points of this project is the withdrawal, the deposit, and the transfer operations.

Each of these operations has their own business logic for calculating banking fees for the given operation.


perform white box testing on the following class:

FeesCalculator.java class in the bank.utils package: The focus here is to check for the correct calculation of fees while performing withdrawal, deposit, and transfer.
For withdrawal: Compute the slice based on the criterion FinalUse(fee) (i.e the statement return(fee)), and develop test cases that perform statement coverage on the resulting set of the statements in the computed slice.  For your analysis, you can ignore the call to round function.
For deposit: Compute the DU-Paths for the variable interestPercentage in the statement double interest = amount * interestPercentage;. For each such path create the test cases that perform condition coverage on the resulting set of the statements in each such DU-Path.
For transfer: Compute and apply the test cases that result from basis path testing.
