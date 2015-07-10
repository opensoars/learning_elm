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
``` elm
-- Single line string
"Hello!"

-- Multiple line string
"""
Hello World,

How are we doing today?
"""
```

### Chars
``` elm
'z'
```
```
'z' : Char
```

### Numbers
``` elm
-- Data type number, until we decide what to do with it.
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
``` elm
[1, 2, 3]
['a', 'b']
[[1], [2]]
```

### Tuples
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

