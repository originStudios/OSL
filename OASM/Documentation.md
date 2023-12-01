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
prnt "hello, how are you"
hello:
```

## Maths

Maths functions set the acc variable to their result
```
add 3,2
sub 10,4
```

## Variables

You can use a variable in a command with {varname}
so you can run `prnt {varname}`
same goes for all other command inputs, anything in curly brackets will be counted as a variable

this includes

`equl hel{lo,wo}w`
this only counts as one input because the middle part has been replaced with it's variable value

```
set varname,vardata
```
