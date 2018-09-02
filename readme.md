# some useful math functions for linux calculator bc

## usage

Put `bcrc` somewhere such as ~/.bcrc, then start bc as follows:
```sh
# you may add an alias to your bashrc file:
#   alias bc='bc -q -l <(cat ~/.bcrc)'
bc -l <(cat ~/.bcrc)  
```

## supported functions

### trigonometric functions
```sh
sin(x), cos(x), tan(x), cot(x), sec(x), csc(x)
```

### inverse trigonometric functions
```sh
arcsin(x), arccos(x), arctan(x), arccot(x), arcsec(x), arccsc(x)

or asin(x), acos(x), atan(x), acot(x), asec(x), acsc(x)
```

### logarithmic function
```sh
log(a, b)
ln(x)            # log(e, x)
lg(x), log10(x)  # log(10, x)
log2(x)          # log(2, x)
```

### others
```sh
e(x), exp(x)     # exponentiation of e
pow(a, b)        # a ^ b
sqrt(x)          # x ^ 1/2
cbrt(x)          # x ^ 1/3
abs(x)           # absolute value of x
fac(n)           # factorial of n
c(n, k)          # n choose k, unordered
a(n, k)          # n choose k, ordered
```
