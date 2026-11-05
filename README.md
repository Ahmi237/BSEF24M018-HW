# Book Store — ASP.NET Core MVC (.NET 10)

**Student:** Muhammad Ahmer  
**Roll number:** BSEF24M018

## Requirements
- .NET 10 SDK
- Visual Studio 2026 Community version 18.0 or newer with **ASP.NET and web development** workload
- OR an editor and the .NET 10 SDK (command line works without Visual Studio)

## Run in Visual Studio
1. Extract the ZIP.
2. Open `BookStore/BookStore.sln`.
3. Select the `https` launch profile.
4. Press **Ctrl+F5** (or F5).
5. Open the local address displayed by Visual Studio.

## Run in a terminal
From the `BookStore` folder:
```powershell
dotnet restore
dotnet run
```

## Assignment mapping
- Task 1: `Models/Author.cs`, `Models/Book.cs`, static seeded lists in `Controllers/HomeController.cs`.
- Task 2: `ViewModels` and `HomeController.Index`, passing `HomeViewModel` to `Index.cshtml` via `@model`.
- Task 3: `Views/Shared/_Layout.cshtml`, `_ViewStart.cshtml`, Home/About/Contact routes, personalized footer.
- Task 4: optional `Styles` / `Scripts` sections, different layouts for About and Contact.
- Task 5: normal HTML POST forms, cards, add/remove methods and confirmation JavaScript.

## Notes
- **No tag helpers** are used. Forms use plain HTML `method`, `action`, and `name` attributes.
- No database is needed. All data is stored in static `List<T>` collections while the app runs.
- Local SVG images under `wwwroot/images` are included and used for the banner, logo, and book covers.
- Bootstrap is loaded from a CDN and needs an internet connection for its CSS; the custom CSS and images are local.
- `.NET 10` targeting requires **Visual Studio 2026** (18.0+) for Visual Studio development. If you only have Visual Studio 2022, install VS 2026 or use the .NET 10 SDK from the CLI.
