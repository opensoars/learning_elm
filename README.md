# learning_elm
Learning me some Elm.

---


## Comments
``` elm
-- Single line comment

{-
  Multiple line comment
-}
```


## Data types

### Strings
Single line strings are written with double quotes, multiple line strings are written with tripple double quotes.
``` elm
"Hello!"

"""
Hello World,

How are we doing today?
"""
```

### Chars
Chars use the single quote notation.
``` elm
'z'
```
```
'z' : Char
```

### Numbers
A pure number such as `5` will be of type `number` until it is turned into an `int` or `float`.
``` elm
5
71393
```
```
> 5
5 : number
```
#### Int
```
> 5 // 2
2 : Int
```
#### Float
``` elm
2.5
5.43455
```
```
> 5 / 2
2.5 : Float
```

### Booleans
``` elm
True
False
```

### Lists
Standard array like functionality, one diffence: lists can only contain one data type. 
``` elm
[1, 2, 3]
['a', 'b']
[[1], [2]]
```

### Tuples
Data structure which can contain multiple data types, unlike lists.
``` elm
("Tests succes", true)
```



## Functions

### Single line
``` elm
isMoreThanZero n = n > 0
```
```
> isMoreThanZero 5
True : Bool
> isMoreThanZero -5
False : Bool
```


### Multiple lines
``` elm
> isMuch n = \
|   if n > 9999 then "Yeah, quite a lot!" else "Please, gimme more.."
```
```
> isMuch 100
"Please, gimme more.." : String
> isMuch 10000
"Yeah, quite a lot!" : String
```

