# Overview for `SecurityService`

## Description

Service to handle window security flags, primarily for blocking screenshots.

## Members

- **_isAndroid**: `bool`
- **_windowManager**: `WindowManagerWrapper`
## Constructors

### Unnamed Constructor
Constructor for [SecurityService].

 **params**:
 * `isAndroid`: Optional override for Android platform check (for testing).
 * `windowManager`: Optional override for [WindowManagerWrapper] (for testing).

