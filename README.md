# Prime-number-checker
I recreated one of my first ever programs that check if an integer is prime or not

I figured out that the most efficient way to find if x is prime, is by only considering
integers up to (and including) the square root of x. This is due to the fact that all
of the factors of x map between values on the interval of <a href="https://www.codecogs.com/eqnedit.php?latex=2\leq&space;\sqrt&space;x&space;\leq&space;x." target="_blank"><img src="https://latex.codecogs.com/gif.latex?.

what this means is that since the factors of a non prime number are paired,
we can look at the smaller factors that reside on the interval of 2 <= x^(1/2).
this is becuase there are no two factors that are >x^(1/2) and multiply to x

<a href="https://www.codecogs.com/eqnedit.php?latex=2&space;\leq&space;x^{1/2}&space;,&space;x{1/2}&space;\leq&space;x" target="_blank"><img src="https://latex.codecogs.com/gif.latex?2&space;\leq&space;x^{1/2}&space;,&space;x{1/2}&space;\leq&space;x" title="2 \leq x^{1/2} , x{1/2} \leq x" /></a>
