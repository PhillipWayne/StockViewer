StockViewer
===========

A simple stock chart viewer. It was originally released at http://zetacentauri.com

![Stock Chart Viewer Screenshot 1](https://github.com/Xangis/StockViewer/blob/master/Images/CSCVScreen1.png)

![Stock Chart Viewer Screenshot 2](https://github.com/Xangis/StockViewer/blob/master/Images/CSCVScreen2.png)

![Stock Chart Viewer Screenshot 3](https://github.com/Xangis/StockViewer/blob/master/Images/CSCVScreen3.png)

A prebuilt Windows installer is available in the Installer directory.

The Stock Chart Viewer is written using C# and .NET 2.0.  It builds and runs on Windows.
A project is included for Visual Studio 11. It doesn't have any complicated dependencies,
so you can create a project for an earlier version simply by including the source files.

An installer scripts for the Nullsoft Install System (NSIS) is included, but you'll
probably have to modify the paths in order for it to work.

This program acquires data from Yahoo or Google finance via their web APIs, which could
change at any time. Those APIs and data feeds have their own licenses which probably say
something about non-commercial use. It's up to you to figure out whether what you're doing
is permitted.
