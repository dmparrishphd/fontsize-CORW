pt.i
====

Given an integer index, return the corresponding font size in points.

Usage
-----

    pt.i(i)
    
| Argument: | :Description       |
|         i | An `integer` index |

Value
-----

The point size as a `double`.

If the corresponding `double` value would be larger than the greatest `double` value
with at a precision of at least `1`, `NA_real_` is returned.

Details
-------

The font sizes are based on a quasi pentatonic scale.
The first five size are 5, 6, 7, 8, and 9.
The next five are the doubles of the first;
the third five are the quadruples of the first (or the doubles of the second),
and so forth.

See Also
--------

[LaTeX Font Size](https://latex-tutorial.com/changing-font-size/)
