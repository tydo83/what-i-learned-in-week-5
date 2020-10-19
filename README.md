# What I learned in week 5

## Mapping, filtering, and reducing
---
![SuperGoodImage](https://i.stack.imgur.com/ufv6k.png)

## For...of
---
```
for(const elementName of arrayName) {}
```
* index i is used for hitting each element
* but in most case, you don't usually need it.
* for...of is made for this. It doesn't access each value, but hit every elements in a loop. 

## function expression
```
const name = function(parameter) {}
```
* has no hoisting
* can't be overwritten if declared with const
* looks like what it is -- a value

## Scope
---
* What happens in function, stays in function
* Variables are only accessible in that block or one block down

## Power refactoring
--- 
```
num * num * num == math.pow(num, 3) == num ** 3
/// find cube num
```

## object and property
---
* collection of thing
* is useful for characteristic

```
const a = {
    a: 0
    b: 1
    c: 2
}
```

### [' '] notation
---
* you can use illegal property name
like number starting name or space.
* also can be used when using dynamic key

## string interpolation
---
String interpolation is replacing placeholders with values in a string literal. The string interpolation in JavaScript is performed by template literals (strings wrapped in backticks ` ) and ${expression} as a placeholder.

## Three ways to check if an object has a property 
---
1. hasOwnProperty() method 
2. in operator
3. comparing with undefined

## Remove property from an object
---
```
delete object.key
```

## How to map an object without changing original value?
---
### Make new object!!
