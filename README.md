# picompanion

Windows companion for pimatrix. Creates virtual monitors and sends them as RTMP signals to pimatrix.

Extracted from `jsilvanus/pimatrix` (`packages/windows-companion`). Status: phase A, copied as-is, not yet built or tested on Windows. The C# client (`Services/PiMatrixClient.cs`) still talks to the pimatrix API by hand; it will move to a contract client generated from pimatrix OpenAPI.

Virtual display driver: see `Assets/Driver/README_DRIVER.md`.
