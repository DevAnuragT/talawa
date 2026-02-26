# Overview for `FakeFlutterSecureStorage`

## Description

A fake implementation of [FlutterSecureStorage] for testing.

 This class provides an in-memory storage implementation that avoids
 global state pollution from `FlutterSecureStorage.setMockInitialValues()`.
 Each instance maintains its own isolated storage map, making tests
 safe to run in parallel (sharded environments).

 **Usage:**
 ```dart
 test('example', () async {
   final fakeStorage = FakeFlutterSecureStorage();
   final service = SecureStorageService(storage: fakeStorage);
   await service.writeToken('key', 'value');
   expect(await service.readToken('key'), 'value');
 });
 ```

## Dependencies

- Fake, FlutterSecureStorage

## Members

- **_storage**: `Map<String, String>`
