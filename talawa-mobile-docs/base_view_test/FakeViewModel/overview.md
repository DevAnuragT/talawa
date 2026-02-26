# Overview for `FakeViewModel`

## Description

FakeViewModel is a test double that extends ChangeNotifier.
 This allows us to test BaseView's lifecycle methods without
 depending on real ViewModels.

## Dependencies

- ChangeNotifier

## Members

- **isDisposed**: `bool`
  Flag to track if dispose was called

