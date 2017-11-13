# Bernstein-Polynomials
Solutions to differential equations can be approximated by series with the terms of the series being calculated via recursion formulas. Unfortunately these algorithms (the recursions) are rarely of practical use in evaluating the series solution as they run into numerical precision problems. This is due to the limitations of floating point arithmetic, as presently implemented in modern processors. This paper demonstrates that by solving the recursion by the use of high precision arithmetic, the series solution can be accurately evaluated. This solution can then be approximated by Bernstein polynomials. This approximation to the original problem uses only machine precision. 
