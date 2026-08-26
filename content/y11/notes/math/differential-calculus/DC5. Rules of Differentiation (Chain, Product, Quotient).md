---
tags:
  - Note
date: 2026-08-26
---
> [!Abstract] Preamble
> The equations and working out provided have been peer-reviewed (with student going under alias “Planks3D”) and checked with graphing technology (e.g. [Desmos](https://desmos.com/calculator)). Please contact the author if there are mistakes with the questions.
> 
> (Remember, error analysis is one way of learning Math!)
# The Chain Rule
This rule is utilised with functions in the form of $f(x)^n$.
## Reference Sheet Formulae
These are from the Mathematics Advanced 2027 Sample reference sheet.
$$
y=f(x)^n -> "dy"/"dx"=n f'(x)[f(x)]^(n-1) \
y=g(u), "where" u=f(x) -> "dy"/"dx"="dy"/"du" times "du"/"dx"
$$

## Other Formulae
These are other forms of the same rule.
$$
h(x)=f(g(x)) -> h'(x)=f'(g(x)) times g'(x) \
"dy"/"dx" = "dy"/"du" times "du"/"dx"
$$

> [!Abstract] Explanation
> In layman’s terms, you basically:
> - Bring down the magnitude of n
> - Multiply f(x) by n
> - Multiply the equation by f’(x)
## Application

> [!Example]
> > [!Example] Simpler Example
> > Before continuing with the more complex example below, you can refer to this as a simpler example.
> > 
> > Let $y=(x^2+2x)^2$.
> > $$
> > y=(x^2+2x)^2
> > $$
> > Utilise the chain rule.
> > $$
> > y=(2x+2)(x^2+2)^1 \
> > therefore y=(2x+2)(x^2+2)
> > $$
> 
> Let $y=7/(sqrt(9x-2))$.
> $$
> y=7/(sqrt(9x-2))
> $$
> Firstly, simplify the function.
> $$
> = 7/(9x-2)^(1/2) \
> = 7(9x-2)^(-(1)/(2))
> $$
> When you have simplified the function, apply the chain rule (with or without a formula, up to you).
> $$
> "dy"/"dx"=n f'(x)[f(x)]^n-1 \
> =7 times -1/2 times 9 times (9x - 2)^(-(3)/(2)) \
> = -63/2(9x-2)^(-3/2) \
> = -63/2 times 1/(sqrt(9x-2)^3) \
> therefore "dy"/"dx" = -63/(2sqrt(9x-2)^3)
> $$

# The Product Rule
This rule is used for the derivative of two multiplied functions. For example, $f(x)g(x)$.

## Reference Sheet Formula
This is from the Mathematics Advanced 2027 Sample reference sheet.
$$
"dy"/"dx" = u ( "dv")/("dx") + v ("du")/("dx")
$$
## Other Formulae

$$
"d"/"dx" [h(x)] = f(x)g'(x) + g(x)f'(x) \
"dy"/"dx"=u' v + v' u \
"dy"/"dx"=v u' + u v' \
"If" h(x) = f(x)g(x) -> h'(x)=f'(x) g(x) + f(x) g'(x)
$$

## Application
> [!Note]
> In these examples, the following form for product rule is utilised and preferred. However, please use the other formulas as you wish or when appropriate (such as when the question asks in terms of $h(x)$ or $"dy"/"dx"$).
> $$
> "dy"/"dx"=u'v+v'u \
> "If" h(x) = f(x)g(x) -> h'(x)=f'(x) g(x) + f(x) g'(x)
> $$

> [!Example] Example (w/o Chain Rule)
> Let $f(x)=(2x+7)(x^3+4x)$.
> $$
> f(x)=(2x+7)(x^3+4x)
> $$
> Usually, you would use short-hand differentiation (or the power rule), but using such methods is tedious and inefficient. Instead, you can utilise the product rule.
> 
> Firstly, define $u$ and $v$, as they are the main pronumerals of this formula. Then, find the derivative of each defined function.
> $$
> u = 2x+7 \
> u' = 2 \
> \
> v=x^3+4x \
> v'=3x^2+4 \
> $$
> 
> After defining $v$ and $u$, substitute it into the formula of the product rule.
> $$
> f'(x)=u'v+v'u \
> = (2) times (x^3+4x) + (3x^2+4) times (2x+7) \
> = 2x^3+8x + 6x^3+21x^2+8x+28 \
> therefore f'(x)=8x^3+21x^2+16x+28
> $$

> [!Example] Example (w/ Chain Rule)
> Let $h(x)=(x+1)(2x+2)^3$.
> $$
> h(x)=(x+1)(2x+2)^3
> $$
> Differentiate with the product rule by first finding $f(x)$ and $g(x)$, and their respective derivatives.
> $$
> f(x)=x+1 \
> f'(x)=1 \
> \
> g(x)=(2x+2)^3 \
> g'(x)=3 times 2(2x+2)^2 \
> =6(2x+2)^2
> $$
> Substitute each variable into the product rule.
> $$
> h'(x)=f'(x)g(x) + g'(x)f(x) \
> h'(x)=1 times (2x+2)^3 + 6(2x+2)^2 times (x+1) \
> therefore h'(x)= (2x+2)^3 + 6(2x+2)^2(x+1)
> $$
# The Quotient Rule
This rule is used for the derivative of two functions divided by each other. For example, $f(x)/g(x)$.

## Reference Sheet Formula
This is from the Mathematics Advanced 2027 Sample reference sheet.
$$
y= u/v -> "dy"/"dx" =  (v "du"/"dx" - u "dv"/"dx")/v^2
$$
> [!Tip]
> Basically, if there is a function ($y= f(x)/g(x)$), then it is $y=u/v$.
## Other Formulae
$$
h'(x)=(g(x) f'(x) - f(x) g'(x))/([g(x)]^2) \
"dy"/"dx"=(v u' - u v')/(v^2) \
"dy"/"dx"=(u'v - v'u)/(v^2)
$$

> [!Important]
> The order is important for the quotient rule. $v$ or $g(x)$ **MUST** come first.
## Application
> [!Note]
> In these examples, the following form for product rule is utilised and preferred. However, please use the other formulas as you wish or when appropriate (such as when the question asks in terms of $h(x)$ or $"dy"/"dx"$).
> $$
> "dy"/"dx"=(u'v-v'u)/(v^2)
> $$

> [!Example]
> Let $y=(x^2+2)/(7x+4)$.
> $$
> y=(x^2+2)/(7x+4)
> $$
> To apply the quotient rule, it requires the defining of variables such as $u$ and $v$, as well as their derivatives. However, unlike the product rule, the order of variables **DOES** matter. Ensure that $v$ or $u’$ comes first, otherwise, you will have a different answer.
> 
> > [!Tip] Tip Regarding Defining $u$ and $v$
> > While this strategy was taken from a lecture, it’s good to remember $u$ as the numerator because the letter ‘u’ is in n**u**merator. This is good for defining $u$, as $u$ will always be the function in the numerator. You can define $v$ as the denominator.
> 
> $$
> u=x^2+2 \
> u'=2x \
> \
> v=7x+4 \
> v'=7
> $$
> Then, substitute each variable into the quotient rule.
> $$
> "dy"/"dx"=(u'v-v'u)/(v^2) \
> = ((2x) times (7x+4) - (7) times (x^2+2))/((7x+4)^2) \
> therefore "dy"/"dx" = (2x(7x+4) - 7(x^2+2))/((7x+4)^2)
> $$

---

# Miscellaneous
These are items that are not fully relevant to the rest of the note.

> [!Danger] Experimental Product Rule Example (w/ Chain Rule)
> **THIS HAS NOT BEEN VALIDATED. PLEASE DO NOT USE THIS AS YOUR MAIN SOURCE OF REFERENCE.**
> 
> Let $f(x)=(4x^2+7x)(6x^3+7)^2$.
> $$
> f(x)=(4x^2+7x)(6x^3+7)^2
> $$
> Differentiate f(x) using the product rule by first defining $u$ and $v$.
> $$
> u = 4x^2+7x \
> u' = 8x+7 \
> \
> v = (6x^3+7)^2 \
> v' = 2 times 18x^2 times (6x^3+7)^1 \
> = 36x^2(6x^3+7) \
> = 216x^5 + 252x^2
> $$
> After defining $u$ and $v$, substitute each into the product rule.
> $$
> f'(x)=u'v+v'u \
> f'(x)=(8x+7) times (6x^3+7)^2 + (216x^5+252x^2) times (4x^2+7x) \
> f'(x) = (8x+7)(6x^3+7)^2 + (216x^5+252x^2)(4x^2+7x)
> $$
> 
> Thanks to another student’s input (“Planks3D”), there are two options. You can either leave it as is if it’s for 2 marks, or expand if it’s for 3 marks or more. (There will be no expanded answer for this example.)