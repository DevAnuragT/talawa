# Method: `minLen`

## Description

Validates that the string has a minimum length.

 By default, whitespace is counted. Set [trim] to `true` to trim leading/
 trailing whitespace before checking length (useful for names but NOT for
 passwords where spaces may be valid characters).

 **params**:
 * `v`: The string to validate.
 * `n`: The minimum length.
 * `trim`: Whether to trim whitespace before checking. Default: `false`.

 **returns**:
 * `String?`: Error message if invalid, null otherwise.

## Return Type
`String?`

## Parameters

- `v`: `String?`
- `n`: `int`
- ``: `dynamic`
