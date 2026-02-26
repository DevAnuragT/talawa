# Method: `createUserFromJson`

## Description

Creates a User from test JSON with nested structure handling.

 **params**:
 * `json`: Map containing user data, may be nested under 'user' key
 * `fromOrg`: Whether to use organization-specific user parsing (default: true for test data)

 **returns**:
 * `User?`: User instance or null if json is null

## Return Type
`User?`

## Parameters

- `json`: `Map<String, dynamic>?`
- ``: `dynamic`
