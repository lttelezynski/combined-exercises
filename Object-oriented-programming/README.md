Exercises for Object oriented programming
-----------------------------------------

### Shapes

Let us imagine that we need to handle some geometric shapes for a program These could be circles, squares, triangles, etc. Properties we need to know about the shapes are their circumference and area. These properties can be calculated from properties of the shapes, but the calculations are different for each shape.

So for our shapes, we want (at least) an interface that gives us two functions: `circumference` and `area`. The default functions, where we have no additional information about an object aside from the fact that it is a shape, are meaningless so should raise an error (check the `stop` function for this), but each specialised shape should implement these two functions.

Implement this protocol/interface and the two functions for at least circles and rectangles; by all means, more shapes if you want to.

``` r
## Your code and tests here
```

### Polynomials

Write a class that lets you represent polynomial objects. An *n*-degree polynomial is on the form *c*<sub>0</sub> + *c*<sub>1</sub> \* *x* + *c*<sub>2</sub> \* *x* \* *x* + ⋯ + *c*<sub>*n*</sub> \* *x* \* *x* \* ⋯ \* *x* and can be represented by the *n* + 1 coefficients (*c*<sub>0</sub>, *c*<sub>1</sub>, …, *c*<sub>*n*</sub>). Write the interface such that you can evaluate polynomials in any point *x*, i.e. with a function `evaluate_polynomial(poly, x)` that gives you the value of the polynomial at the point `x`.

The function `uniroot` (built into R) lets you find the roots of a general function. Use it to write a function that finds the roots of your polynomials. This function works by numerically finding the points where the polynomial is zero. For lines and quadratic polynomials, though, there are analytical solutions. Write special cases for such polynomials such that calling the root finding function on the special cases exploits that solutions are known there.

``` r
## Your code and tests here
```
