# Overview for `MainScreenTourViewModel`

## Description

ViewModel managing app tour flow, tutorial targets, and dialogs.

 Handles tour initialization, progression, and completion tracking.

## Dependencies

- BaseModel

## Members

- **keys**: `MainScreenKeys`
  Reference to MainScreenKeys.

- **onTabTapped**: `void Function(int)`
  Callback to switch tabs.

- **showAppTour**: `bool`
  Show tour flag.

- **tourComplete**: `bool`
  Tour complete flag.

- **tourSkipped**: `bool`
  Tour skipped flag.

- **transitionDelay**: `Duration`
  Transition delay for testing.

- **context**: `BuildContext`
  Context set in initializeTour. Check mounted before use.

- **appTour**: `AppTour`
  App tour instance.

- **targets**: `List<FocusTarget>`
  List of focus targets for the current tour step.

## Constructors

### Unnamed Constructor


