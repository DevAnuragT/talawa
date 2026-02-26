# Overview for `CacheEntry`

## Description

A container representing a cached item with its production timestamp.

## Members

- **value**: `T`
  The cached data value.

- **ts**: `DateTime`
  The timestamp when this entry was created or updated.

 TODO: Implement TTL logic using this timestamp.

## Constructors

### Unnamed Constructor
Creates a [CacheEntry] with the given [value] and the current time.

