# Selection Sort

## Preparation
- Choose six NUMBERs at random
- Place the NUMBERs between 0 and 5 on ARRAY INDEX at random

## Steps
- Set VARIABLE i to 0 on DIAL P
- On a separate paper, make a const using VARIABL len, then write value 6
- While i is less than len-1, repeat the following
    - On DIAL Q, place VARIABLE min at the current value of i
    - On DIAL R, plase VARIABLE j at i+1
    - While j is less than len, repeat the following
        - If the NUMBER at j is less than the NUMBER at min, then
            - Update min with the value of j
        - Increase j by 1
    - Swap the NUMBER at i with the NUMBER at min
    - Increase i by 1 