# cis165-lab2

Program                  	Values used  	        Expected result before running	Actual output	Match or fix
sum.cpp — assigned values	50 and 100           	150	                            150	          Match
sum.cpp — changed values	5 and -10  	          -5                             	-5           	Match
mpg.cpp — assigned values	312 miles; 16 gallons	19.5	                          19.5	        Match
mpg.cpp — changed values	5 miles, 8 gallons  	0.625                          	0.625        	Match

First, a number is assigned to integer1, then a number is assigned to integer2. The variable "total" is then declared. Next, the sum of integer1 and integer2 is assigned to total. Finally, total is printed. The calculation is stored to total before printing because this is considered good practice, for example in case one would want to use the variable's value again later.

First, a number is assigned to gallons, then a number is assigned to gallons. The variable "mpg" is then declared. The variables are of the float data type so that the quotient is also a float. If a C++ program performs division using two integer operands, the quotient is truncated at the decimal point. To show this, when the data type of the operands is float, the quotient is 19.5, but when it's int, the quotient is just 19 without the precision of the tenths place.
