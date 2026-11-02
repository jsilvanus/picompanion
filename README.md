# virtual-screen-streamer

(Formerly `picompanion`.) A Windows program that runs on the operator PC, creates virtual monitors and streams many virtual screens as RTMP to pimatrix. It is not a Node project and not a Pi service: in the [piecosystem](https://github.com/jsilvanus/piecosystem) it is a **seam** project, meeting the Pi ecosystem at RTMP.

Extracted from `jsilvanus/pimatrix` (`packages/windows-companion`). Status: phase A, copied as-is, not yet built or tested on Windows. The C# client (`Services/PiMatrixClient.cs`) still talks to the pimatrix API by hand; it will move to a contract client generated from pimatrix OpenAPI.

Virtual display driver: see `Assets/Driver/README_DRIVER.md`.
