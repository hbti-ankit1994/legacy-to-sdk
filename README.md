Licensed under the MIT License — see LICENSE file for details.

# csproj SDK Converter
A fully client-side tool that converts legacy `.csproj` files to modern SDK-style format. No server, no data sent anywhere — runs entirely in the browser.

**[Live demo → https://hbti-ankit1994.github.io/legacy-to-sdk/**

## Features
- 4 built-in examples (class library, ASP.NET WebApi, WinForms, console app)
- SDK target selector (`.NET.Sdk`, `.Sdk.Web`, `.Sdk.Worker`, `.Sdk.Razor`)
- TFM override (auto-detect or pin to net8.0, net6.0, netstandard2.0, etc.)
- Nullable / ImplicitUsings toggles
- Diff view (new lines highlighted)
- Conversion log with timestamped entries
- Download output as `.csproj`
- Drag & drop `.csproj` files
- Confidence score for migration

## License
MIT
