# Overview for `MainScreenKeys`

## Description

Central registry of all GlobalKeys used across MainScreen and its components.

 This class contains zero logic and serves as a pure data holder for UI keys.
 Separating keys from ViewModels improves testability and makes it easier
 to mock UI bindings in tests.

## Members

- **scaffoldKey**: `GlobalKey<ScaffoldState>`
  Scaffold key for the main screen.

- **keyBNHome**: `GlobalKey`
  Key for home bottom navigation button.

- **keyBNDemoHome**: `GlobalKey`
  Key for demo home bottom navigation button.

- **keySHPinnedPost**: `GlobalKey`
  Key for pinned post on home screen.

- **keySHPost**: `GlobalKey`
  Key for post on home screen.

- **keySHOrgName**: `GlobalKey`
  Key for organization name on home screen.

- **keySHMenuIcon**: `GlobalKey`
  Key for menu icon on home screen.

- **keyDrawerCurOrg**: `GlobalKey`
  Key for current organization in drawer.

- **keyDrawerSwitchableOrg**: `GlobalKey`
  Key for switchable organization in drawer.

- **keyDrawerJoinOrg**: `GlobalKey`
  Key for join organization button in drawer.

- **keyDrawerLeaveCurrentOrg**: `GlobalKey`
  Key for leave current organization button in drawer.

- **keyBNEvents**: `GlobalKey`
  Key for events bottom navigation button.

- **keyBNDemoEvents**: `GlobalKey`
  Key for demo events bottom navigation button.

- **keySECategoryMenu**: `GlobalKey`
  Key for category menu on events screen.

- **keySEDateFilter**: `GlobalKey`
  Key for date filter on events screen.

- **keySEAdd**: `GlobalKey`
  Key for add button on events screen.

- **keySECard**: `GlobalKey`
  Key for event card on events screen.

- **keyBNPost**: `GlobalKey`
  Key for post bottom navigation button.

- **keyBNDemoPost**: `GlobalKey`
  Key for demo post bottom navigation button.

- **keyBNChat**: `GlobalKey`
  Key for chat bottom navigation button.

- **keyBNProfile**: `GlobalKey`
  Key for profile bottom navigation button.

- **keyBNDemoProfile**: `GlobalKey`
  Key for demo profile bottom navigation button.

- **keySPEditProfile**: `GlobalKey`
  Key for edit profile on profile screen.

- **keySPAppSetting**: `GlobalKey`
  Key for app settings on profile screen.

- **keySPHelp**: `GlobalKey`
  Key for help on profile screen.

- **keySPDonateUs**: `GlobalKey`
  Key for donate us on profile screen.

- **keySPInvite**: `GlobalKey`
  Key for invite on profile screen.

- **keySPLogout**: `GlobalKey`
  Key for logout on profile screen.

- **keySPPalisadoes**: `GlobalKey`
  Key for Palisadoes on profile screen.

- **keyBNFunds**: `GlobalKey`
  Key for funds bottom navigation button.

