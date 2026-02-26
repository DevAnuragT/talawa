# Overview for `MainScreenNavViewModel`

## Description

ViewModel managing bottom navigation, page construction, and tab switching.

 Responsibilities:
 - Build navigation bar items with localization and keys
 - Construct page widgets (demo vs. regular mode)
 - Handle tab switching and current page state
 - Manage demo mode exit logic

## Dependencies

- BaseModel

## Members

- **keys**: `MainScreenKeys`
  Reference to MainScreenKeys for accessing GlobalKeys.

- **pages**: `List<Widget>`
  Contains the Widgets to be rendered for corresponding navbar items.

- **navBarItems**: `List<BottomNavigationBarItem>`
  Actual [BottomNavigationBarItem]s that show up on the screen.

- **currentPageIndex**: `int`
  Current page index in the bottom navigation.

## Constructors

### Unnamed Constructor
Constructs MainScreenNavViewModel with required dependencies.

 **params**:
 * `keys`: MainScreenKeys instance for accessing GlobalKeys

