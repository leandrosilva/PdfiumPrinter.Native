# PdfiumPrinter.Native

Convenient way to add [PDFium](https://github.com/bblanchon/pdfium-binaries/releases) binaries to your own projects, courtesy of [Benoît Blanchon](https://github.com/bblanchon). Thanks mate.

The goal is to keep it reasonably up to date.

## Try it locally

If you'd like to contribute to this project, and so, need to test it locally, you can do the following:

1) Add a local source to `%appdata%\NuGet\NuGet.Config`:

```
    <add key="local" value="C:\Users\darwin\Documents\NuGet\Packages" />
```

2) Pack the project (right click, "Pack" on the `PdfiumPrinter.Native` project)

3) Install it locally:

```
    nuget add .\PdfiumPrinter.Native.1.0.0.nupkg -source C:\Users\darwin\Documents\NuGet\Packages
```
