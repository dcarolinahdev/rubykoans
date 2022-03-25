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
