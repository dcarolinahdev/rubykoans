# Rubykoans

## Versions

This quickstart project have these versions:

- Ubuntu 20.04.4 LTS
- ruby 2.7.1

## Sections

### Minitest Assertions

`assert(test, [failure_message])`

Here the assertion/keyword *assert* is used to check if something (first parameter) is true.

The second parameter may be a string or a proc. If msg is a String, it will be used as the failure message. Otherwise, the result of calling msg will be used as the message if the assertion fails.

`assert_equal( expected, actual, failure_message = nil )`

Ensures if expected is equal to actual. An optional failure message may be provided as the final argument.

The first parameter can be a result and the second parameter can be a proc.

## Booleans

In Ruby, only false and nil are **false** everything else is **true**.

## Nil

**nil** is a special value that indicates **the absence of a value** – it is Ruby’s way of referring to “nothing”. An example of when you will encounter the nil object is when you ask for something that doesn’t exist or cannot be found.

## Strings

- double quoted and single quoted strings are strings.

- length method includes/count breaklines.

- **lines** method count as a line every string finished in a breakline.

- you can use the syntax `my_string[a, b]` for print my_string from character a to b characters.

- the operators + and << will concatenate two strings.

- the operator += will concatenate to the end of a string.

- a string copy don't modify the original string.

- the operator << modifies the original string.

- double quoted string interpret escape characters, but single quoted string doesn't.

- you can interpolate variables only in a double quoted string as: "The value is #{value}"

- these syntaxs get the same result because **two points syntax includes the last position in string, three points syntax doesn't**

> string = "Bacon, lettuce and tomato"
>
> string[7,3]
>
> string[7..9]

- strings are unique objects, therefore their 'object_id' are the same.

## Symbols

- two variables with the same content are the same symbol, therefore their have the same object_id.

- method names are internally stored as symbols.

- respond_to? is a useful method to know when a method is applied to a object.

## Arrays

- the operator << can add an element to the end of an array.

- when an array is accessed with positive index it starts from left to right from zero, otherwise it starts from the right from -1.

- it may be useful to access the first and last elements of an array with :first and :last methods.

- you can use the `my_array[a, b]` syntax to print my_array from element "a" (read 2nd observation) to a maximum number of "b" elements if they exist.

if you try to access from element on index my_array.length, the result is empty, but if you try to access from a higher index, the result is nil.

- you can create a range (or convert it to an array) with a two points syntax that includes at most the parameter with the second index, or with a three points syntax without including it.

- you can push and element to last position, and pop it with the methods :push and :pop.

- :unshift method appends elements passed in as arguments to the front of the original array. It is one of the methods in Ruby that changes the original array.

- :shift method removes the first element of an array and returns the removed element. If an array is empty and the shift() method is called on it, the method returns nil.

## Array assignment 

- in parallel assignment, if there are extra values, these are not assigned.

if you use the splat_operator, these extra values are assigned in an array.

if you get too few values, corresponding values are assigned to nil.

- you can swapping values with parallel assignment.

## Objects

- All in Ruby are objects, and every object has different id.

- :inspect method can return a string that describes the object in an understandable way.

- :clone method creates a different object.
