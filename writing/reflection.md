# Data Types

## Gabriel Salvatore Xavier Saccoccio

## Program Output

### What is the output from running the following commands?

- `python demonstrate-variable-limitations.py`

``` plaintxt
The value of a feasible number is 115792089237316195423570985008687907853269984665640564039457584007913129639936

The value of another feasible number is 179769313486231590772930519078902473361797697894230657273430081157732675805500963132708477322407536021120113879871393357658789768814416622492847430639474124377767893424865485276302219601246094119453082952085005768838150682342462881473913110540827237163350510684586298239947245938479716304835356329624224137216
```

- `python compare-variables.py`

``` plaintxt
1.0 is not the same as 1.1
1.0 is the same as 1.0
.33333 + .33333 + .33333 is not equal to 1
.33333333333 + .33333333333 + .3333333333 is not equal to 1
The value of 1/3 is 0.3333333333333333
0.3333333333333333 + 0.3333333333333333 + 0.3333333333333333 is equal to 1
1/3 + 1/3 + 1/3 is equal 1
```

## Program Questions

### Why is it not feasible to perform the computation `2**2**100`?

The computation `2**2**100` involves raising 2 to the power of 2 raised to the power of 100, resulting in an astronomical number with an impractical number of digits. The size of the result poses significant challenges, including excessive memory requirements for storage, an extremely long computational time due to the vast number of operations involved, and difficulties in representing or displaying such a large number within the constraints of typical computing systems. Dealing with computations of this magnitude often exceeds the practical limits of current technology and requires specialized approaches for handling extremely large or small numbers.

### What is the value of `1/3` according to the Python language? Why?

The value of `1/3` is a float poiting number according to the python language. The `/` division operator
performs floating point division, meaning that if you divide two integers, it will result in an floating
point number.

### Why is the value of `.33333 + .33333 + .33333 == 1` equal to `False`?

Because of the way floating point numbers works in computers. Doing the sum of 
.33333 + .33333 + .33333, the sum might not be exactly 1, due to rounding errors in the representation of these decimal fractions in binary.
