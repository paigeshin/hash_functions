# hash_functions

### Hashing Functions

Hashing functions are functions that map input data of some arbitrary size to `fixed-size` output values. 

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e758f0db-42e8-433e-8dda-57cc803fd5bf/Untitled.png)

⇒ Same character length  

### Cryptographic hash functions

1. One-way function which is infeasible to invert
2. Small change in input yields large change in the output 
3. Deterministic - same input yields same output
4. Unlikely to find 2 outputs with same value

### SHA - 1

Git uses a hashing function called SHA-1 (though this is set to change  eventually).

- SHA-1 always generates 40-digit hexadecimal numbers
- The commit hashes we’ve seen a million times are the output of SHA-1
