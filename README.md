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

To answer them, first convert the answer list into english

1. $f(n)\in O(g(n))$, but $f(n)\not \in \Omega(g(n))$
This is equivalent to saying $f(n)$ grows slower than $g(n)$
2. $f(n)\in \Omega(g(n))$, but $f(n)\not \in O(g(n))$
This is equivalent to saying $f(n)$ grows faster than $g(n)$
3. $f(n)\not\in O(g(n))$, and $f(n)\not \in \Omega(g(n))$
This is equivalent to saying $f(n)$ isn't growing slower than $g(n)$ and  $f(n)$ isn't growing faster then $g(n)$. 
4. $f(n)\in \Theta (g(n))$
This is equivalent to saying $f(n)$ grows at a rate that is a constant multiple of $g(n)$

$f(n)= 10n + 3\log_{15} n > g(n)= 4n - 2\log_2 n$, $\forall n > 1$ so the answer is 4.
$f(n) = 2n^5 >> g(n) = 5n^2$  so the answer is 2.
$f(n)=\log_{10} \left(n^{10}\right) << g(n)=n$ so the answer is 1
$f(n)= 4n^5 >> g(n)= 5n^4$ so 2.
$f(n) = 10^{256} << g(n) = \log n$ so 1.
$f(n)= n^2 << g(n)= 2^n$ so 1.

| $f(n)=\ldots$              | compared to | $g(n)=\ldots$          |
|----------------------------|:-----------:|------------------------|
| $f(n)=n$                   | 1           | $g(n)=2n^2 + n$        |
| $f(n)= 10n + 3\log_{15} n$ |4            | $g(n)= 4n - 2\log_2 n$ |
| $f(n) = 2n^5$              |2            | $g(n) = 5n^2$          |
| $f(n)=\log_{10} \left(n^{10}\right)$ | 1 | $g(n)=n$ |
| $f(n)= 4n^5 $ | 2 | $g(n)= 5n^4$ |
| $f(n) = 10^{256}$ | 1 | $g(n) = \log n$ |
| $f(n)= n^2 $ | 1 | $g(n)= 2^n$ |

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.

I used this site for the definitions of O, Omega, and Theta. I had only seen big O before:
https://www.geeksforgeeks.org/difference-between-big-oh-big-omega-and-big-theta/

I also plotted the functions on desmos
