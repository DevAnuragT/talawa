# Overview for `MainScreenViewModel`

## Description

MainScreenViewModel serves as a coordinator for the main screen.

 This class follows the composition pattern to delegate responsibilities
 to specialized ViewModels while maintaining backward compatibility with
 existing widgets and tests.

 Responsibilities are delegated to:
 - [MainScreenKeys]: All GlobalKeys (zero logic)
 - [MainScreenNavViewModel]: Navigation, pages, tabs, demo mode
 - [MainScreenTourViewModel]: App tour, targets, dialogs, tutorial flows

## Dependencies

- BaseModel

## Members

- **keys**: `MainScreenKeys`
  Instance of MainScreenKeys for GlobalKey access.

- **navViewModel**: `MainScreenNavViewModel`
  Instance of MainScreenNavViewModel for navigation logic.

- **tourViewModel**: `MainScreenTourViewModel`
  Instance of MainScreenTourViewModel for tour logic.

## Constructors

### Unnamed Constructor
Constructs MainScreenViewModel with optional dependencies for testing.

### _internal
Internal constructor for dependency injection (primarily for testing).

#### Parameters

- ``: `dynamic`
- ``: `dynamic`
- ``: `dynamic`
### createForTest
Creates test instance with consistent dependency injection.

 **params**:
 * `keysInstance`: Optional MainScreenKeys
 * `navInstance`: Optional MainScreenNavViewModel
 * `tourInstance`: Optional MainScreenTourViewModel

 **returns**:
 * `MainScreenViewModel`: Test instance

#### Parameters

- ``: `dynamic`
- ``: `dynamic`
- ``: `dynamic`
