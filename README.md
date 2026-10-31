# OurLauncher

OurLauncher is an open-source, portable Minecraft: Java Edition launcher for Windows.

## Project status

The repository contains the initial .NET 10 and WPF solution structure. Launcher features are under development.

## Planned features

- Minecraft Java Edition version manifest and installation
- Offline profiles and Microsoft account authentication
- Automatic Java runtime detection and management
- RAM and launch settings
- Portable application data mode
- Future support for mod loaders such as Fabric and Forge

## Development requirements

- Windows 10 or Windows 11
- .NET 10 SDK

## Build and run

```powershell
dotnet build OurLauncher.sln
dotnet run --project src/OurLauncher.UI/OurLauncher.UI.csproj
```

## License

Licensed under GNU GPL v3. See [LICENSE](LICENSE).
