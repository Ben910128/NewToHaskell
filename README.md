# NewToHaskell


## Background
Have heard Haskell as a programing language for a long time but never learned it.
By an accident, it is required to apply for a job opportunity, so here to log useful
resourse found for reference.  


## Resourse
- What exactly Haskell is? [Home Page](https://www.haskell.org)
**An advanced, purely functional programming language**
**Declarative, statically typed code.**

```hs
primes = filterPrime [2..]
  where filterPrime (p:xs) =
          p : filterPrime [x | x <- xs, x `mod` p /= 0]
```
Very strange the demo is not `hello world`, diffcult to guess the meaning of demo code at first glance.

- Google: Please tell me [How to Learn Haskell](https://acm.wustl.edu/functional/haskell.php)
- First Book: [Learn you a Haskell for Great Good](http://learnyouahaskell.com/)


