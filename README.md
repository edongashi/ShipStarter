## About
This is a visual studio project template to support mixed script and dll output for ShipScript. 

Class library output (lib.dll) and everything inside the /src/Library/script directory are moved to /output on build. All files and directories in /script are copied by default so modifying build actions for them is not necessary.

Even if the class library is not needed, it can be exploited to reference NuGet packages which can be required from script.
