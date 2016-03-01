# Polynomials
From the previous lesson: **polynomial** is an expression consisting of constants and variables joined by multiplication, addition or subtraction with non-negative integer exponents.

### Distributive property
Multiplication is distributive over addition and subtraction.

```
a × (b + c) = ab + ac
```

The formal definition sounds so:

> Multiplication over addition (and subtraction too) when it's left- and right distributive, and since multiplication is **commutative** the left-distributivity is enough to say it's distributive over addition.

Left distributive is shown above and *right-distributive* means

```
(b + c) × a = ba + ca
```

For multiplication on the set of *real numbers* the following is true:

```
a × (b + c) = (b + c) × a
```

since its commutativity:

```
ab × ac = ba × bc
```

#### Formal logic application

It is interesting that disributivity and commutativity seem to apply to formal logic statements as well as for arithmetics.

### Parenthesis

In fact parenthesis are used to indicate *implied multiplication* of theirs contents by `1` if the sign before them is `+` and by `-1` if the sign is `—` (the whole expression in the parenthesis is negative).

```
(3 + x) = 1 × (3 + x) = 3 + x
```

but

```
-(3 + x) = -1 × (3 + x) = -3 - x
```

That's why parenthesis opening with the minus behind them requires terms signs' inversion.

### Distributive property application
The multiplication distributive property is used to find the product of polynomials multiplication.

```
(2x + 3)(x - 1) =
2x(x - 1) + 3(x - 1) =
2x² - 2x + 3x - 3 =
2x² - x - 3
```

> To multiply polynomials one should multiply each term of the first one by each term of the second one.

~~I think this is the reason for **square equations** to be so called, as it's calculated by the polynomials multiplication~~, e.g.

```
(2x - 1)² =
(2x - 1)(2x - 1) =
2x(2x - 1) - (2x - 1)
4x² - 2x - 2x + 1
4x² + 1
```

And the `4x² + 1` is a square equation.

**The above conclusion** about reasoning of square equation to be called so seems to be wrong, because the equation *should have been called so* by its *degree*, and the degree of a polynomial equals the largest degree of its terms. Thus the equation with `degree = 2` should be called square.

### Guessing polynomial product degree and term count

Once you have a polynomial multiplied with anything else it may be useful to know what should product's degree equal to and how many terms should it consist of.

```
2x(4x + 3) → degree = 2, terms = 2
```

Checking:
```
2x(4x + 3) = 8x² + 6x → correct!
```

The degree and number of terms within the polynomials multiplication product can be found as:
* multiplying terms count by each other (which is done during the actual calculation) → this gives us *term count*
* finding two biggest degree terms from each of the multiplication operands and computing degree of their's product


## Questions
* why does the triangle inscribed into the rectangle area always equal rectangle's area divided by two?

## Lesson timing

*March 1, 2016*

*The lesson itself took 1:50, practical question about 50 minutes aand abstracting about half an hour.*