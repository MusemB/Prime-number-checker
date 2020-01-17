# Prime-number-checker
I recreated one of my first ever programs that check if an integer is prime or not

I figured out that the most efficient way to find if x is prime, is by only considering
integers up to (and including) the square root of x. This is due to the fact that all
of the factors of x map between values on the two intervals of <a href="https://www.codecogs.com/eqnedit.php?latex=2\leq\sqrt&space;x,\sqrt&space;x<&space;x" target="_blank"><img src="https://latex.codecogs.com/gif.latex?2\leq\sqrt&space;x,\sqrt&space;x<&space;x" title="2\leq\sqrt x,\sqrt x< x" /></a>

what this means is that since the factors of a non prime number are paired,
we can look at the smaller factors that reside on the interval of <a href="https://www.codecogs.com/eqnedit.php?latex=2\leq\sqrt&space;x." target="_blank"><img src="https://latex.codecogs.com/gif.latex?2\leq\sqrt&space;x." title="2\leq\sqrt x." /></a>
this is becuase there are no two integers that are >x^(1/2) and multiply to x

here is my proof of it:

## definiton of a prime:
a set of prime numbers <a href="https://www.codecogs.com/eqnedit.php?latex=(\mathbb{P})" target="_blank"><img src="https://latex.codecogs.com/gif.latex?(\mathbb{P})" title="(\mathbb{P})" /></a>
is defined to contain natural numbwers that have the property 
a prime number is only divisible by itself and 1.

let a be s.t <a href="https://www.codecogs.com/eqnedit.php?latex=2&space;\leq&space;a&space;\leq&space;\sqrt&space;x" target="_blank"><img src="https://latex.codecogs.com/gif.latex?2&space;\leq&space;a&space;\leq&space;\sqrt&space;x" title="2 \leq a \leq \sqrt x" /></a>

let b be s.t <a href="https://www.codecogs.com/eqnedit.php?latex=\sqrt&space;x&space;\leq&space;b&space;\leq&space;x" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sqrt&space;x&space;\leq&space;b&space;\leq&space;x" title="\sqrt x \leq b \leq x" /></a>

if x is non-prime, then <a href="https://www.codecogs.com/eqnedit.php?latex=a*b&space;=&space;x" target="_blank"><img src="https://latex.codecogs.com/gif.latex?a*b&space;=&space;x" title="a*b = x" /></a>

let c be some int > 0

let k = x^(1/2)+c
let s = x^(1/2)

k*s = x+c*x^(1/2)
therefore x < k*s
QED.
