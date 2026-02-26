# Method: `get`

## Description

Retrieves a value from the cache by its [key].

 Returns null if the key is not found or has expired (if expiration logic is added).

 **params**:
 * `key`: The unique key to identify the cached value.

 **returns**:
 * `T?`: The cached value if found, null otherwise.

## Return Type
`T?`

## Parameters

- `key`: `String`
