# AprioriAlgorithm

1. Find all unique values in table

2. Find number of occurences of each value in
set of all rows i.e. How many rows does the
value show up in?

3. Calculate support for each unique value (freq/#rows)

4. Filter out values that don't meet min support.

5. Using remaining values, create every combination of values of Tuple size 2

6. Calculate support for each unique value

7. Filter out values that don't meet min support

8. Using remaining values, create every combination of values of Tuple size 3

9. repeat steps 6-8 then continue with combination of TupleSize+1  until there
are no longer any sets that meet minimum support




Alg logic:

Set initial tuple size to 1, find unique values in table then find tuples that achieve minimum support
TupleSize++ then using leftover values find tuples that achieve minimum support
Repeat until no new tuples achieve minimum support
