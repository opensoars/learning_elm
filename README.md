# Functions

## Single line
``` elm
isMoreThanZero n = n > 0
```

```
> isMoreThanZero 5
True : Bool
> isMoreThanZero -5
False : Bool
```


## Multiple lines
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

