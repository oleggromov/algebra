# Equations

**Equation** is an equality (two expressions combined with the *equals* `=` sign) containing 1 or more variables.

`18 - x = 12` is an equation.

**Solving an equation** means to determine value(s) of variable(s) which make the equality true.

Equations differ from *identities* because identities are always true while equations become true only with the appropriate variables' values.

Identity, for example, is `x - 3 = x - 2 - 1`.

### Kinds of equations
* conditional equations (`n + 1 = 2`), which are true only with specific variable values;
* identities
* something that is not an equation (`y - 3 = y`), that definitely cannot be true but was written using the equals sign by mistake.

> Sometimes while posing a question there're too many points only a few of which can be actually useful. Thus the first step of solving a problem is to decide which information should be payed attention to.

### The meaning of equations

Equation written in a number-n-variable form

`c = 1000 + 15x`

is just a handy mathematical representation of some statement and probably real-world problem. For example, the equation shown above can be stated as follows: *total cost of production consists of $1000 fixed expense for an order placement and $15 for each manufactured piece*.

Once you substitute the actual value of produced pieces you can simply calculate the actual production cost.

### Transitivity
Equality is a relation between some objects. In mathematics **equality is a transitive relation** which means if `a = b` and `b = c` then `a = c`.
There're some other more precise definitions of *transitivity* in the sets theory, but it's too complicated for this stage of learning.

## Solving an equation

To solve an equation one should modify both sides of it in the same way in order to get a simplified form, where, for instance, variables are on the left-hand side and constants on the RHS.

Example:

```
3(x + 2) = 12 - 2x    | / 3
x + 2 = 4 - 2x/3      | + 2/3x
x + 2/3x + 2 = 4
5/3x + 2 = 4          | - 2
5/3x = 2              | / 5/3
x = 6/5
```

In the above example it's shown how different operations are sequentially applied to the both sides of the equation to get rid of variable on the right side and then simplify the equation to express actually one x.

> Using *improper* fractions helps expression simplifying, especially substitution.

#### Example with multiplication

```
3(2x + 4) = 2(x - 5)
6x + 12 = 2x - 10      | - 2x - 12
4x = -22
x = -5.5
```

If equation includes the multiplication it can be handy to distribute it first to make further simplification even simpler.


#### Example with fractions

```
2/3x + 5 = 17x - x     | * 3
2x + 15 = 51 - 3x      | + 3x - 15
5x = 36
x = 36/5
```

Fractions are a bit awkward to manipulate with, therefore multiplication by the *reciprocal* of the needless fraction (`5/3` has a reciprocal of `3/5`) is often useful.

## Interesting

> Dividing by zero leads to all sorts of problems and inconsistencies.

### Polynomails product

`(ax + b)(ax - b) = a²x² - b²`

It is interesting, that:

- the coefficient near `x²` is a positive square
- the coefficient near `x` is always zero

The last statement is true because of the standard form of the *2nd degree polynomial* which looks like `ax² + bx + c`, and in the above polynomial we can observe the absense of `x` which can be represented with any `x` multiplied by `0`.

### Repeating decimals to fractions

It was told ealier in the course that *any repeated decimal can be converted into a fraction.* Let's try to prove this statement.

For example, we try to prove if `0.33..` can be represented by a fraction. So, let `x = 0.33..`, where points on the tail stand for infinitely repeated numerals.

```
x = 0.33..            | * 10
10x = 3.33..          | -x
10x - x = 3.33.. - x
9x = 3.33.. - 0.33    // we can just subtract the actual x value
9x = 3
x = 3/9
x = 1/3
```

So we proved that `0.33..` can be presented as a fraction.

#### Surprising `0.99..`

Let's try to make the same transformations for an `0.99..` number.

```
x = 0.99..             | * 10
10x = 9.99..           | -x
9x = 9
x = 1
```

Wow! WAT?!

The same proof can be found for any decimal ending with infinitely repeated `.99..` - it will always equal the nearest larger integer value.

## Lesson timing

*March 7, 2016*

The theory took 1:30, practical questions — 0:50, solving problem set for 1-4 lessons — 1:50, abstracting — 0:40.