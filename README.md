jsoncpp.natvis
==============
It is a file, which sets some rules for Visual Studio debugger
and instucts it to visualize JsonCpp (https://github.com/open-source-parsers/jsoncpp) 
objects in a special manner.
With such visualizer reading of the debugging JSON values became
much easier, because of compact data representation.

Supported Versions
------------------
I've tested it with jsoncpp 1.8.0 on Visual Studio 2017
and currently have no information could it be run on other versions.

How to install
--------------
There are several ways to deploy natvis file. The easiest one
is to copy jsoncpp.natvis to the %USERPROFILE%\My Documents\Visual Studio 2017\Visualizers.
You have to create Visualizaers folder if it does not exist.

More information about creation of custom views
-----------------------------------------------
https://docs.microsoft.com/en-us/visualstudio/debugger/create-custom-views-of-native-objects?view=vs-2019
