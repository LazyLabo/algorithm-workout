# Insertion Sort

## Preparation
- Choose six NUMBERs at random
- Place the NUMBERs between 0 and 5 on ARRAY INDEX at random

## Steps
- Set VARIABLE i to 1 on DIAL P
- While i is less than 6, repeat the following
    - Place VARIABLE tmp somewhere on the table, then move the NUMBER at i under VARIABLE tmp
    - On DIAL Q, place VARIALBE j, and set it to the value of i-1
    While j is greather than or equal to 0, AND the NUMBER at j is greater than tmp, repeat the following
        - Move the NUMBER at j to j+1
        - Decrease j by 1
    Move the NUMBER of tmp to j+1
    Increase i by 1