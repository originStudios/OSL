OASM is originOS's own assembly language

This is meant to be as optimised as possible so it runs super quickly


## Program Control

jump label
(Goes immediately to the line that the specified label was on)

exit output
(Exits the entire project with the provided error code)

## Output

prnt text goes here

## Variables

setv vaiablename,variablevalue

## Conditional Jumps

Value1 and Value2 are compared and if the condition is fulfilled, the program jumps to the line with the inputted label on it

```
2 Values

command value1,value2,label

equl (==)
cmre (>)
cmrq (>=)
clss (<)
clsq (<=)
neql (!=)

1 Value

command value,label

exst (Checks if the program can access a file with a specified name)
```

example:

This script will not print anything because 1 is equal to 1 and it skips to the hello label

```
equl 1,1,hello
prnt hello, how are you
hello:
```

## Expressions

You can put expressions inside exclamation marks

example:

prnt 10 + 5 = !10 + 5!

Basic Expressions

+ - * / % (Add Minus Multiply Divide Modulus)

or (returns true if either of the two items on either side of the "or" are equal to true)

and (returns true if both of the items on either side of this "and" are equal to true)

nor (returns true if the items on either side of the "nor" have only one item that is true)
