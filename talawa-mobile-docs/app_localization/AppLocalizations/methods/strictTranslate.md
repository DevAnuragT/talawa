# Method: `strictTranslate`

## Description

Translates the given key to a localized string, returning the key if not found.

 Unlike [translate], this method never returns null. If the key is not found,
 the key itself is returned as a fallback.

 **params**:
 * `key`: The translation key

 **returns**:
 * `String`: The translated string or the key itself as fallback

## Return Type
`String`

## Parameters

- `key`: `String`
