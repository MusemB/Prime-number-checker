# Prime-number-checker
I recreated one of my first ever programs that check if an integer is prime or not

I figured out that the most efficient way to find if x is prime, is by only considering
integers up to (and including) the square root of x. This is due to the fact that all
of the factors of x map between values on the two intervals of <a href="https://www.codecogs.com/eqnedit.php?latex=2\leq\sqrt&space;x,\sqrt&space;x<&space;x" target="_blank"><img src="https://latex.codecogs.com/gif.latex?2\leq\sqrt&space;x,\sqrt&space;x<&space;x" title="2\leq\sqrt x,\sqrt x< x" /></a>

what this means is that since the factors of a non prime number are paired,
we can look at the smaller factors that reside on the interval of <a href="https://www.codecogs.com/eqnedit.php?latex=2\leq\sqrt&space;x." target="_blank"><img src="https://latex.codecogs.com/gif.latex?2\leq\sqrt&space;x." title="2\leq\sqrt x." /></a>
this is becuase there are no two natural numbers, where one of them is >x^(1/2) and multiply to x

here is my proof of it:

## definiton of a prime:


a set of prime numbers <a href="https://www.codecogs.com/eqnedit.php?latex=(\mathbb{P})" target="_blank"><img src="https://latex.codecogs.com/gif.latex?(\mathbb{P})" title="(\mathbb{P})" /></a>
is defined to contain natural numbers that have the following property:

#### a prime number is only divisible by itself and 1.

assume that <a href="https://www.codecogs.com/eqnedit.php?latex=a,b\in\mathbb{N}\;&space;|&space;\;&space;a\oplus&space;b>\sqrt&space;x&space;\;&space;and\;&space;a*b=x" target="_blank"><img src="https://latex.codecogs.com/gif.latex?a,b\in\mathbb{N}\;&space;|&space;\;&space;a\oplus&space;b>\sqrt&space;x&space;\;&space;and\;&space;a*b=x" title="a,b\in\mathbb{N}\; | \; a\oplus b>\sqrt x \; and\; a*b=x" /></a>

let a be s.t  <a href="https://www.codecogs.com/eqnedit.php?latex=2&space;\leq&space;a&space;\leq&space;\sqrt&space;x" target="_blank"><img src="https://latex.codecogs.com/gif.latex?2&space;\leq&space;a&space;\leq&space;\sqrt&space;x" title="2 \leq a \leq \sqrt x" /></a>

let b be s.t  <a href="https://www.codecogs.com/eqnedit.php?latex=\sqrt&space;x&space;<b\leq&space;x" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sqrt&space;x&space;<b\leq&space;x" title="\sqrt x <b\leq x" /></a>

if x is non-prime, then <a href="https://www.codecogs.com/eqnedit.php?latex=a*b&space;=&space;x" target="_blank"><img src="https://latex.codecogs.com/gif.latex?a*b&space;=&space;x" title="a*b = x" /></a>

let <a href="https://www.codecogs.com/eqnedit.php?latex=c\in\mathbb{N}|c>1" target="_blank"><img src="https://latex.codecogs.com/gif.latex?c\in\mathbb{N}|c>1" title="c\in\mathbb{N}|c>1" /></a>

let <a href="https://www.codecogs.com/eqnedit.php?latex=k=\sqrt&space;x&space;&plus;c" target="_blank"><img src="https://latex.codecogs.com/gif.latex?k=\sqrt&space;x&space;&plus;c" title="k=\sqrt x +c" /></a>

let <a href="https://www.codecogs.com/eqnedit.php?latex=s&space;=&space;\sqrt&space;x" target="_blank"><img src="https://latex.codecogs.com/gif.latex?s&space;=&space;\sqrt&space;x" title="s = \sqrt x" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=k*s&space;=&space;x&plus;c(\sqrt&space;x&space;)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?k*s&space;=&space;x&plus;c(\sqrt&space;x&space;)" title="k*s = x+c(\sqrt x )" /></a>

which results in <a href="https://www.codecogs.com/eqnedit.php?latex=x&space;<&space;k*s" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x&space;<&space;k*s" title="x < k*s" /></a>

However, this contrudicts our assumption stated that <a href="https://www.codecogs.com/eqnedit.php?, which must mean that 

at least one of the factors
  
QED.
