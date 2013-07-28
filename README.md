StockViewer
===========

A simple stock chart viewer.

A compiled, installable version of the Champion Stock Chart Viewer is available at:

http://zetacentauri.com/software_stockchartviewer.htm

The Stock Chart Viewer is written using C# and .NET 2.0.  It builds and runs on Windows.
A project is included for Visual Studio 11. It doesn't have any complicated dependencies,
so you can create a project for an earlier version simply by including the source files.

An installer scripts for the Nullsoft Install System (NSIS) is included, but you'll
probably have to modify the paths in order for it to work.

This program acquires data from Yahoo or Google finance via their web APIs, which could
change at any time. Those APIs and data feeds have their own licenses which probably say
something about non-commercial use. It's up to you to figure out whether what you're doing
is permitted.
