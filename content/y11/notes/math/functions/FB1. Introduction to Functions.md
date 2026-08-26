---
tags:
  - Note
date: 2026-08-26
---
# Functions (Basics)
Welcome to what you should know about functions. In this note, you will find:
- [[#Functions and Relations]] → information about what a function and relation is
- [[#Function Notation]] → how functions are notated
- [[#Piecewise Functions]] → how function notation can be used for piecewise functions, a type of function that involves different functions at certain intervals
- [[#Domain and Range]] → what the domain and range of a function is, and how it is notated
- [[#Even and Odd Functions]] → what an even and odd function is

---
# Functions and Relations
## Relations
Relations are when the elements of one set have an association with elements of the other set. This can be represented through a set of ordered pairs, a table of values, or a graph.
## Functions
Functions are a special type of [[#Relations|relation]] in which every value of x only corresponds with one value of y. This places x as the independent variable, whilst y is the dependent variable.

In order to test if a relation is a function, you can use the vertical line test. You can do this by placing a function of $x=n$ (a vertical line at $n$), where $n$ is the x-value you want to test.
# Function Notation
Since y depends on x (or y is a function of x), we can notate y as $y=f(x)$. Where there are different values of x, we can find f. For example, the value of $f$ at $x=4$ can be notated as $f(4)$.

$$
y=f(x)
$$
# Piecewise Functions
Piecewise functions are functions that are formed out of 2 or more functions at different intervals of the function’s domain.

> [!Example]
> Take $f(x)=cases(x^2 "for" x gt.eq 1, 2x "for" x<1)$. Find $f(1)$ and $f(-2)$.
> $$
> f(x)=cases(x^2 "for" x gt.eq 1, 2x "for" x<1)
> $$
> $f(1)$ can be found by determining the function at that interval. The corresponding function for $f(1)=x^2$. Then, substitute 1 into $f(x)=x^2$.
> $$
> f(1)=(1)^2=1
> $$
> Take the same process for $f(-2)$.
> $$
> f(-2)=2(-2)=-4
> $$
# Domain and Range
The domain of a function is all x-values where $f(x)$ is defined.

The range of a function is all y-values where $f(x)$ is defined.

To describe the domain and range of a function, you can use the following notations.
## Interval Notation
Interval notation utilises “\[]” \(square brackets) and “()” (brackets) to describe the end values of a function. Square brackets means it **includes** the end values of that interval, whereas round brackets do **not** include the end values.

> [!Example]
> Find the domain of $f(x)=x^2$.
> 
> $$
> therefore D: (-infinity, infinity), R: [0, infinity)
> $$
> 
> You can provide proof to this domain by using graphing technology. Try inputting $f(x)=x^2$ into a graphing technology, like Desmos.
## Inequalities and Other Formats
You can describe the domain and range of a function by using inequalities, such as $-1<x< -1$. You can also describe it by saying $"all real x"$, $"all real y"$, and $y gt.eq 0$.
# Even and Odd Functions
## Even Functions
Even functions are symmetrical by the y-axis (creating a mirror line). This means that the graph does not change when it is reflected by the y-axis. Thus, for $x=a$ and $x=-a$, the y-value is the same.

This can be proved by following the rule $f(x)=f(-x)$.

> [!Example]
> Determine whether $f(x)=x^2$ is odd or even.
> 
> $$
> f(x)=x^2 \
> f(-x)=(-x)^2 \
> f(-x)=x^2 \ 
> therefore f(x)=f(-x)
> $$

## Odd Functions
Odd functions are symmetrical by the x-axis (establishing a mirror line). This means that if the graph is reflected by the x-axis, it does not change. Thus, for $x=a$ and $x=-a$, the values of y are flipped (e.g. $x=a, y=-b$, $x=-a, y=b$).

This can be proved through following the rule $f(-x) = -f(x)$.

> [!Example]
> Determine whether $f(x)=x^3$ is odd or even.
> 
> $$
> f(x)=x^2 \
> f(-x)=(-x)^3 \
> f(-x)=(-x)^3 \
> f(-x)=-x^3 \
> -f(x)=-[x^3] \
> -f(x)=-x^3 \
> therefore f(-x)=-f(x)
> $$
> 
> > [!Warning]
> > Be careful not to use $f(-x)$ to create $-f(x)$. Always derive $-f(x)$ from $f(x).$
> 



