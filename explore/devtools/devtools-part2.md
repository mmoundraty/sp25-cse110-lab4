1. The bug was that the data type of num1 and num2 were not specified so it was treated as a string instead of an integer.
2. I fixed this bug by typecasting num1 and num2 into an int such as Number(num1) & Number(num2).
