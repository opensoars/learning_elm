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

### Numbers
```
-- Data type number, until we decide what to do with it.
5
71393

> 5
5 : number
```
#### Int
``` elm
> 5 // 2
2 : Int
```
#### Float
```
2.5
5.43455
> 5 / 2
2.5 : Float
```

### Booleans
``` elm
True
False
```

### Lists


### Tuples

```
"Hello!" : String
5 : number
5.6 : Float
True : Bool
False : Bool
[1,2,3] : List number
["a","b"] : List String
[[1],[2]] : List (List number)
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

