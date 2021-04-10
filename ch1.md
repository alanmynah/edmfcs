### 1.1 What are each of the following?

(a) Cardinality of set `{0, 1, 2, ,3, 4, 5, 6}`

7

(b) ceil(111/5)

23

(c) floor(5/111)

0

(d) The set of divisors of 100

1, 2, 4, 5, 10, 20, 50

(e) The set of prime divisors of 100

2, 5

### 1.2 Let `f(n)` be the largest prime divisor of `n`. Can it happen that `x < y`, but `f(x) > f(y)`? Give example or explain why it's impossible.

Yes, for `x = 11` and `y = 12`, `f(x) = 11`, `f(y) = 3`.

Trying to extrapolate, for `-5 <= x >= 5` there is always such pair, where x is a prime and y is that prime + 1, where the problem statement would hold true.

### 1.3 Under what circumstances `floor(x) == ceil(x) - 1`?

For all `x` where `x != 0`. For `0`, both floor and ceil are equal.

### 1.4
