# rb_rubykoans

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
