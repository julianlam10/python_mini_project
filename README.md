# Polynomial Derivative Calculator using Python Coding Language
by Julian Lam for CS102 Section C Fall 2021

# Explanation of Project
This calculator works for polynomials with positive, integer exponents. Coefficients may be positive, negative, or 0. Decimals also work.

It first prompts the user for the degree of the polynomial that they wish to take the derivative of, AKA the highest exponent

Then, it will prompt the user for the coefficients of each of the terms (and a constant). The exponents are assumed to be decreasing by one each time, so if a term does not exist, the user may input 0.

For example, a 3rd degree polynomial will prompt the user for the coefficient of the 3rd degree term, then the 2nd, then the 1st, then a constant.

It then computes and outputs the derivative of that polynomial in a single line with plus and/or minus signs, excluding any 0 terms and unnecessary "to the 1 power."
