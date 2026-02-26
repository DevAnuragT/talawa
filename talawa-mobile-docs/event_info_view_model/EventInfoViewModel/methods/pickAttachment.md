# Method: `pickAttachment`

## Description

Pick an attachment from gallery or camera.

 This method provides a clean interface for the View to pick attachments
 without directly accessing the MultiMediaPickerService.

 **params**:
 * `fromCamera`: If true, opens camera; if false, opens gallery

 **returns**:
 * `Future<File?>`: The picked file, or null if cancelled

## Return Type
`Future<File?>`

## Parameters

- ``: `dynamic`
