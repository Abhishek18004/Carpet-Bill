# Carpet Bill Generator – C Program
Carpet Bill Generator is a basic C program application that calculates the cost of carpeting a room based on user-specified dimensions, discounts, and material prices. It aids customers in generating a comprehensive bill with area measurements, installation fees, discounts, and taxes.

## Features
Accepts room length, width, customer discount, and cost per square foot as input

## Calculates:
- Room area
- Installation fees (carpet + labor)
- Subtotal after discount
- Total after tax
- Generates nicely formatted bill with all the details
- Modular code with functions for clean separation of logic

## Tech Stack
- Language: C
- Compiler: GCC or any standard C compiler
- Platform: Console-based

## How to Run
1. Compiling the Program:
``` bash
gcc carpet_bill.c -o carpetbill
```
2. Running the Executable:

``` bash
./carpetbill
```

## Sample input and Output
Sample Input:

``` bash
Length of room (feet)? 15
Width of room(feet)? 12
Customer discount (percent)? 10
Cost per square foot? 75.5
```
Sample Output:
``` bash
                                MEASUREMENT
                 Length                            15 feet
                 Width                             12 feet
                 Area                              180 feet

                                CHARGES

DESCRIPTION                     COST/SQ.FT                        CHARGE
-----------                     ----------                        -------
Carpet                          75.50                             Rs 13590.00
Labour                          28.35                             Rs 5103.00
                                                                -------
INSTALLED PRICE                                               Rs 18693.00
Discount                        10                                Rs 1800 
                                                                -------
SUBTOTAL                                                      Rs 16893.00
Tax                                                           Rs 1435.91
TOTAL                                                         Rs 18328.91
```

## Project Structure
``` bash
carpet_bill.c     # This has the Main code file containing all logic and functions
README.md         # Project documentation
```

## Developed By
Abhishek Karthik