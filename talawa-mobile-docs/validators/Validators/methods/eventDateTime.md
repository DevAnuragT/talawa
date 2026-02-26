# Method: `eventDateTime`

## Description

Validates that event end date/time is not before start date/time.

 **params**:
 * `startDate`: The start date of the event.
 * `startTime`: The start time of the event.
 * `endDate`: The end date of the event.
 * `endTime`: The end time of the event.

 **returns**:
 * `String?`: Error message if end date/time is before start date/time, null otherwise.

## Return Type
`String?`

## Parameters

- `startDate`: `DateTime`
- `startTime`: `TimeOfDay`
- `endDate`: `DateTime`
- `endTime`: `TimeOfDay`
