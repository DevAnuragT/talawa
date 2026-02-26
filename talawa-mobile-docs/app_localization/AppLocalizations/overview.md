# Overview for `AppLocalizations`

## Description

Provides methods to localize the application, making it available to users with different languages.

## Members

- **_localizedStrings**: `Map<String, String>`
- **locale**: `Locale`
  The locale for localization.

- **isTest**: `bool`
  Whether this is being used in a test environment.

- **delegate**: `LocalizationsDelegate<AppLocalizations>`
  Static member to have a simple access to the delegate from the MaterialApp.

## Constructors

### Unnamed Constructor
Creates an [AppLocalizations] instance with the given [locale].

 **params**:
 * `locale`: The locale for localization
 * `isTest`: Whether this is being used in a test environment

 **returns**:
   None

