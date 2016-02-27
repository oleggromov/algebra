# Expressions

A **term** is a bunch of *variables* or *constants* or both that are multiplied together. For example, each of

* `2x`
* `x`
* `2`

is a term.

> Mathematical convention of writing terms is about writing coefficient first with variables after them appearing in ascending alphabetical order.

**Expression** is a combination of terms.


### Factors
**Factor** is any term another term can be divided by or another term can be multiplied by to get the initial one.

For example, for the term `5x × 7y × 2z` any of the below terms is a factor:

* `5`
* `5x`
* and even `5x7z`

**Coefficient** is a constant factor.

> Number `1` is a factor for any term.

### Simplifying terms

In order to simplify terms one should know about *operation commutativity*. Commutative operation is an operation for which order of its operands doesn't matter. Both *multiplication* and *addition* have commutativity property.

This means that

* `a + b = b + a`
* `a × b = b × a`

for any combination of operands.

#### Examples

`5x × 7y × 2z = 70xyz`

`4x × y × -3x = -12x²y`

> The exponential notation `x³` is read as „x for the third“ (power).

### Combining like terms

Terms can be combined if and only if:

* they have exactly the same variable(s)
* with the same power(s)

`15x² + 3x^7 - 7x × 2x - 4 × 2x - 4 × 4 - x × 3 =`

`15x² + 3x^7 - 14x² - 8x - 20 + 3x = `

`x² + 3x^7 - 5x - 20`.

## Polynomials

A **polynomial** is:

* an expression
* consist of constants, variables or both
* combined with `×`, `+` or `—`
* with non-negative integer exponents

Each of the following is a polynomial:

* `5x³ + 1/2xy + 7`
* `z + 6z² + 7 + ax³ + 8×5`
* `4n³ + 3n² + 1`
* and even `4` is technically a polynomial.

### Degrees

**Degree of a term** is sum of exponents of its all variables. E.g.

* `-4x³` has `degree = 3`, is a *third degree term*
* `6 × x^7 × y^4` has `degree = 11`, is an *eleventh degree term*

Terms without variables, e.g. `4`, have a degree of `0` because `4 = 4 × x^0`, i.e. has a variable `x` with exponent `0`.

**Degree of a polynomial** is a highest degree of its terms.

`-12x^7 + 3x² + 64x` is a `7th degree polynomial` because of x for the seventh power.

### Standard form
There's a conventional standard form of writing polynomials from the largest to the smallest degree term, e.g.

`y + 6xy - y³` should be written as

`-y³ + 6xy + y`

> It's important that `6xy` term is the *second degree term* because each of its variables has the exponent of `1` and the sum of exponents equals to `2`.

## Shortcuts

Very interesting that **multiplication** can be considered as just a handy shortcut for *addition*:

`2 + 2 + 2 + 2 + 2 = 5 × 2`

And **exponentiation** in turn is just a shortcut for multiplication:

`2 * 2 * 2 = 2³`

> #### Order of operations
>
> 1. **P** — parenthesis ()
> 1. **E** — exponentiation ^
> 1. **M** — multiplication ×
> 1. **D** — division /
> 1. **A** — addition +
> 1. **S** — subtraction —
>
> Thus the `(-b)^n` not equals to `b^n` because of parenthesis priority over the exponentiation operation.

### Exponentiation

**Exponentiation** is an operation written as `b^n` where `b` is *base* and `n is *exponent*. Exponentiation for the nth means that a number should be multiplied by itself for `n` times. Or in another words exponent shows how many same factors (bases) are multiplied together.

> * `b²` is a *square of b* because the area of `b × b` square is b²
> * `b³` is a *cube of b*

#### Scientific number notation

Scientific number notaion of *decimal numbers* is often used in programming as below:

`30471` can be written as `3.0471 * 10^4` or `3.0471e4`, where `e` stands for *base 10* and `4` stands for exponent.

#### Negative exponents

Negative integer exponent means **undo of multiplication** or **division**, e.g.

`x^-2 = 1/x^2` that equals to `divide by x²`

`1/x^a` is read as „one over x to the power of a“.

`x^-a/a = 1/x^a`

> When one wants to divide by a fraction he should multiply by its reciprocal instead: `1 / a/b = 1 * b/a`.

## Questions
* [why is `-y` a factor of `6x²y³`?](https://discussions.udacity.com/t/lesson-2-end-of-the-chapter-quiz-question-11-factors/43959/5?u=oleggromov)

## Lesson timing

*February 27, 2016*

*The lesson itself took 3 hours and its abstracting about 1 hour.*