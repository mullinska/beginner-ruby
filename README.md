# beginner-ruby

## Table of contents
1. Variables
2. Conditionals
3. Methods

## How to ruby:

#### This is how to define a **variable**:

```
$ x = 10
$ x = "string"
$ x = ["this", "is", "an", "array"]
```

A variable can be used to store a value. This value can be a number, series of letters- a **string**- or it can be an array, which is a series of values.

#### These are **conditions**:
1. "==" Equals.
2. "!=" Non equals.
3. ">" Greater than.
4. "<" Less than.
5. ">=" Greater than or equal to.
6. "<=" Less than or equal to.
7. "||" Or. (if both are true will return true)
8. "^" Xor. (if both are true will return false)
```
if (x != 3)
    x = 3
end

while (x > 0)
    x = x - 1
end
```

Conditions are used to determine if something is true or not by comparing two things.

#### These are **methods**:

By starting off with a _def_, then giving the method a name, we can define a method. The variable in the parenthesis serves as an input you can use with the method later.

```
def my_method(a)
  a + 10
end

my_method(14) will equal 24
```