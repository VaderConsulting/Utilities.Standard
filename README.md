# Utilities.Standard

A cross-platform (.NET Core 3.1) build of the **Utilities** library, using `Microsoft.Windows.Compatibility` for WinForms support.

**Source last updated:** 2020-08-31
**Initiated:** 2019-08-03 · **Target Framework:** .NET Core 3.1

---

## Overview

`Utilities.Standard` (project: `Utilities.Core.csproj`) is a **shared-source** project: it links directly to the source files in the sibling `../Utilities/` folder, ensuring a single source of truth while producing a .NET Core-compatible assembly.

---

## Linked Source Files

`CueTextBox`, `Data`, `DataGridViewEx`, `DataTransferEventArgs`, `TextDrawing`, `Extensions`, `ListboxItem`, `Marquee`, `Serial`, `TransparentTableLayoutPanel`, `TriggeredQueue`

> For full API documentation see the [Utilities](../Utilities) project.

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Utilities.Core` (`Utilities.Core.csproj`) | C# | Class library (netcoreapp3.1, WinForms via Windows Compatibility pack) | Linked-source build of the sibling `Utilities` files listed above |

Only the project file is in this tree; the linked `.cs` files live in the sibling [Utilities](https://github.com/VaderConsulting/Utilities) repo.

## How to open

Clone [VaderConsulting/Utilities](https://github.com/VaderConsulting/Utilities) beside this folder as `Utilities`, then open `Utilities.Core.csproj` in Visual Studio 2019 and build.

## Requirements

- Visual Studio 2019, .NET Core 3.1 SDK
- NuGet: Microsoft.Windows.Compatibility 3.1.1, Microsoft.CSharp 4.7.0, Microsoft.NETCore.Platforms 3.1.2

## Attribution and provenance

Working copy from my Development folder `Utilities.Standard`.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.

