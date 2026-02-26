# Overview for `TestJsonUtils`

## Description

Shared utility class for handling JSON deserialization in tests.

 **Purpose:**
 Provides centralized methods for creating model instances from test JSON data,
 specifically handling nested user structures and complex data relationships
 that appear across multiple test files.

 **Key Features:**
 - Handles nested user structures consistently across all models
 - Uses `fromOrg: true` by default for simplified test user creation
 - Provides null-safe parsing for all optional fields
 - Reduces code duplication across test files
 - Maintains consistent parsing behavior for test scenarios

