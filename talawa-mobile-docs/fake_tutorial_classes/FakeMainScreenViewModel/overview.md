# Overview for `FakeMainScreenViewModel`

## Description

Test double for MainScreenViewModel used by AppTour tests to track tab taps.

 Uses FakeNavViewModel to ensure tab taps are tracked properly.

## Members

- **_delegate**: `MainScreenViewModel`
- **_navViewModel**: `FakeNavViewModel`
## Constructors

### Unnamed Constructor
Creates a fake instance with tracking-enabled navigation.

### _create


#### Parameters

- `_delegate`: `dynamic`
- `_navViewModel`: `dynamic`
