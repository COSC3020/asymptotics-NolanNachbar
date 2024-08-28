# The O, Omega, and Theta

Each row in the table below specifies two functions $f(n)$ and $g(n)$.
Fill in the *number* from this list that best describes their relationship:

1. $f(n)\in O(g(n))$, but $f(n)\not \in \Omega(g(n))$
1. $f(n)\in \Omega(g(n))$, but $f(n)\not \in O(g(n))$
1. $f(n)\not\in O(g(n))$, and $f(n)\not \in \Omega(g(n))$
1. $f(n)\in \Theta (g(n))$

I have done the first one for you, as an example.

| $f(n)=\ldots$              | compared to | $g(n)=\ldots$          |
|----------------------------|:-----------:|------------------------|
| $f(n)=n$                   | 1           | $g(n)=2n^2 + n$        |
| $f(n)= 10n + 3\log_{15} n$ |             | $g(n)= 4n - 2\log_2 n$ |
| $f(n) = 2n^5$              |             | $g(n) = 5n^2$          |
| $f(n)=\log_{10} \left(n^{10}\right)$ |  | $g(n)=n$ |
| $f(n)= 4n^5 $ |  | $g(n)= 5n^4$ |
| $f(n) = 10^{256}$ |  | $g(n) = \log n$ |
| $f(n)= n^2 $ |  | $g(n)= 2^n$ |

$f(n)= 10n + 3\log_{15} n > g(n)= 4n - 2\log_2 n$, $\all n > 1$ so the answer is 4.

I used this site:
https://www.geeksforgeeks.org/difference-between-big-oh-big-omega-and-big-theta/
