# Program to test output with full expression evaluation #

## Language extension ##
We extend the Barebone language with the following instruction
- `out f`: to print the value of *formula* `f`
- `out str`: to print the string *str*
- `in X`: to read an user input for variable `X`
Formula support `+, -, *, /`, brackets `(`, and `)`, and logical operator `&&` (conjuction) and `||` (disjunction).

## Expected result ##
- The final result is `{X = 0}`
- The console should display
```
X is 3
1030
X is 2
X is 1
X is 0
```

*Contributor: tshoang* 
