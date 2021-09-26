# BigInt

In C++, we can use large numbers by using the boost library. We can indeed use different datatypes like int128_t, int256_t, int1024_t etc.
But in C no such features exist.

Therefore, to representing numbers in the range of -2<sup>63</sup>-1 to 2<sup>63</sup>-1 in C, we must build our own datatype called BigInt.

This program successfully implements BigInt in C with the addition and subtraction functionalities.

### Addition: 
- 44 + 55 = 99   
- (-44) + 55 = 11  
- 44 + (-55) = -11  
- (-44) + (-55) = 9


### Subtraction:
- 44 - 55 = -11  
- (-44) - 55 = -99
- 44 - (-55) = 99
- (-44) - (-55) = 11
