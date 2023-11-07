## Selection

```
if (statement) {
    runs if a statement is correct
}

loop (number) {
    runs a number of times
}

until (statement) {
    runs until a statement is correct
}

while (statement) {
    runs until a statement is incorrect
}

when statement {
    like a listener so this code runs when a statement is correct
}

def ("name","commands") {
    defines a basic subroutine
}

func ("name","data-accepted") {
    defines a .commmand()
    leave data-accepted blank for a .command
    input is the value inputted
}
```

## Variables
```
hello[variable.int] = 1
hello."hi" = 2
hello = jsondata
const hello = "hi"
```

## Get Variables
```
hello[10]
hello
hello.key("hi")
file("name" or "path") - returns file as json array
```

## Ui

###
```
setpos x y
set_x x
set_y y

change_pos +x +y
change_x +x
change_y +y
```


```
text.id (text:Hello; size:10; colour:#fff;)

Is the equivalent of:

text.id = {
    "text":"test",
    "layer":1,
    "size":10,
    "colour":#fff
}
```

## Updating Ui Elements

```
id = id.To("String")

text.id.str."layer" = 1
text.id."text" = "fortnite"
text.id."width" = 100

render text.id
text {"text":"test","layer":1,"size":10,"x":x,"y":y,"colour":#ffffff}
square {"width":100,"height":30,"rounding":10,"colour":#202020}
```

## Prefixes
```
! - not
# - len

none - int float variable
"" - string
[] - list
{} - json

hello = "wow"
[hello] = "My variable name is wow"
log(wow) "My variable name is wow"
```

## commands
```
round()
random()
log()
input()
key()


or / |
and / &
not / !
equals ==
set =
minus -
divide /
add +
multiply *
exponentiate ^
```
