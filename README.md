# SolvePolynomial
This Java program reconstructs a polynomial from given shares in JSON format and recovers the secret f(0) using polynomial interpolation.
It also detects inconsistent (bad) shares.
OUTPUT TEST CASE 1
k = 3 (degree m = 2)
Total shares declared (n): 4, shares parsed: 4
Best match count among provided shares: 3
Secret (f(0)) = 3
Polynomial f(x) = (1)*x + (3)
Inconsistent shares at x = [6]

OUTPUT TEST CASE 2k = 7 (degree m = 6)
Total shares declared (n): 10, shares parsed: 10
Best match count among provided shares: 10
Secret (f(0)) = 1556085303637093711775781250000000000000
Polynomial f(x) = (very large coefficients for x^6 + x^5 + ... + constant)
