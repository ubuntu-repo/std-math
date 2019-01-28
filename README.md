# std-math
Standard mathematics library providing common scientific functions.

### Standard Functions
Functions take both floating point and integer values unless otherwise stated
* `math.abs(x)` returns the absolute value (or magnitude) of a number, thus always non-negative
* `math.exp(x)` returns e^x, the natural exponentiation
* `math.log(x)` returns the natural logarithm of x
* `math.sqrt(x)` returns the square-root of x
* `math.pi` is the floating point representation of π within YASL
* `math.cos(x)`, `math.sin(x)`, `math.tan(x)` are their respective trigonometric functions taking an angle in radians
* `math.acos(x)`, `math.asin(x)`, `math.atan(x)` are the inverse trigonometric functions returning an angle in radians in the range [-π/2, π/2]
* `math.ceil(x)` returns the integer closest to x such that it is greater-than or equal-to x
* `math.floor(x)` returns the integer closest to x such that it is less-than or equal-to x
* `math.deg(x)` treats x as an angle in radians and returns the equivalent angle in degrees
* `math.rad(x)` treats x as an angle in degrees and returns the equivalent angle in radians

### Number Theoretic Functions
Function arguments will be type cast to integers unless otherwise specified
* `math.isprime(n)` return true iff n is a positive prime
* `math.gcd(a, b)` return the greatest common divisor of |a| and |b|
* `math.lcm(a, b)` return the lowest common multiple of |a| and |b|
