# Global Functions and Variables

## main

Comprehensive test suite for EventVolunteer model.

 This test file covers two important scenarios:
 1. Testing EventVolunteer.fromJson() directly with the correct data format
    to ensure 100% coverage of the actual model's deserialization logic
 2. Testing TestJsonUtils.createEventVolunteerFromJson() with nested API response format
    to ensure the utility method correctly handles real-world API responses

 Both approaches are necessary because:
 - EventVolunteer.fromJson() expects direct user data (fromOrg: true format)
 - Real API responses often have nested user structures that TestJsonUtils handles
 - We need both the model coverage AND the utility method validation

- **Return Type:** `void`

