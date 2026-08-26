---
tags:
  - Note
math-topic:
status:
date: 2026-08-26
---
# Differentiation from First Principles
To find the derivative function ($f'(x)$) of any function at any x-value:

$$
f'(x)=lim_(h->0)(f(x+h)-f(x))/(h)
$$

This formula works by utilising the central idea of $f'(x)$, where it works by finding the instantaneous rate of change of a function. 

![[DC1. Introduction to Differentiation#^567f6a]]

In this case, $f(b)$, as previously seen in [[DC1. Introduction to Differentiation]], is the **second point** that is used to find the derivative. $f(b)=f(x+h)$.

As **any two points** on the function, $f(x)$ and $f(x+h$) come closer together to where the distance between both points reaches 0 ($lim_(h->0)$), the derivative at one point ($f(x)$) is found, thus $f'(x)$.

$h$ is **any value** that **creates the second point** for $f'(x)$. It is important to remember that if you are only finding the derivative, $h$ is only a constant, and does **not** need to be found.

> [!Example]
> Firstly, establish a function. Let $f(x)$ equal to $x^2+2x$.
> $$
> f(x)=x^2+2x
> $$
> Then, you can find the derivative by first finding the numerator’s components of the following formula.
> $$
> f'(x)=lim_(h->0) (f(x+h)-f(x))/(h)
> $$
>  However, this is not necessary if you’d like to evaluate straight from the formula. For simplicity’s sake, let’s find $f(x+h)$.
> $$
> f(x+h)=(x+h)^2+2(x+h) \
> = x^2 + 2x h + h^2 + 2x + 2h
> $$
> Now that we’ve found $f(x+h)$, we can find $f(x+h)-f(x)$. This helps us complete the numerator for the formula.
> $$
> f(x+h)-f(x)= (x^2 + 2x h + h^2 + 2x + 2h) - (x^2+2x) \
> = cancel(x^2) + 2x h + h^2 + cancel(2x) + 2h cancel(-x^2) cancel(-2x) \
> = 2x h + h^2 + 2h \
> $$
> Now, you can just substitute into the formula.
> $$
> f'(x)=lim_(h->0) (f(x+h)-f(x))/(h) \
> = lim_(h->0) (2x cancel(h) + h^cancel(2) + 2cancel(h))/(h) \
> = lim_(h->0) (2x + h + 2h)
> $$
> Now, you can resolve the limit (by substituting $h=0$).
> $$
> therefore = 2x + 2
> $$
> > [!Tip]
> > Remember **NOT** to resolve the limit before the denominator has been removed, as $h eq.not 0$ in the denominator as a fraction cannot be divided by 0.

> [!Tip]
> You’ll be able to differentiate at a much easier and more efficient way in [[DC4. Short-Hand Differentiation]]. (Please only use first principles in desperate times, such as when the question asks you to do this…)