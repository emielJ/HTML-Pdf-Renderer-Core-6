HTML-Pdf-Renderer-Core-6
=============

Stripped down version of [HTML Renderer Core](https://github.com/polybioz/HTML-Renderer-Core)

Changes:

* Migrated to .NET 6
* Used latest versions of SixLabors.Fonts.dll and SixLabors.ImageSharp.dll to fix problems with rendering PNG images
* Added test program to manually test PDF generation

Todo:

* Bold and Italic do not work on Linux
* Migrate from Webclient to Httpclient
* Dispose all IDisposable objects as soon as possible (i.e. CssBox derivatives)
* Check for thread-safety
* Create NuGet packages when todo list is emptied

License:

BSD 3-Clause "New" or "Revised" License
