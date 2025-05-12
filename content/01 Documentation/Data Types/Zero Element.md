Zero elements are values that, when used in [arrays](https://sheets.wiki/arrays/), have no width and/or height.
# Syntax

| Dimensions | Formula |
| - | - |
| 0 x 1 | `TOCOL(,1)` |
| 1 x 0 | `TOROW(,1)` |
| 0 x 0 | `ARRAY_CONSTRAIN(,,)` |

These zero elements can be useful when used in REDUCE or LAMBDA Recursion when used as an initial value. In some situations, a zero element can essentially remove an initial value from the accumulator.