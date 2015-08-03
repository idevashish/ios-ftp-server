**ios-ftp-server** is a very simple ios Ftp server library written in Cocoa/Objective C that you can include into your
projects to add file access.  It used to be known under another name but for clarity I have renamed it as ios-ftp-server

The latest version can be found in the Source tab, via SVN.  Currently this is in the form of a project which compiles a static library and then creates a demo app using the static lib.

NOTE : the latest version is in Trunk

I have only added a subset of Ftp Commands. You can upload and download files and list the contents of a folder.



Known clients we have got this working with are  [Transmit](http://www.panic.com/transmit/) from Panic and [FileZilla](http://filezilla-project.org/). Cyberduck and Windows Explorer.

I'm releasing this as I want to concentrate on other parts of my app and hope that other people can get involved and
make this into a really useful library for cocoa programmers.

My thanks to Dustin Voss for the AsyncSocket routines which I have used.
AsyncSocket can be found at http://code.google.com/p/cocoaasyncsocket/
and that part is covered by his own copyright that is included in the headers.



LICENSE addendum.
For the purposes of using this library  the intention  of the use of  LGPL for this projects sourcecode is that
I consider and intend the use of the static library to be equivalent to using a dylib and that the code should be compiled as a static lib and linked in that way.  In this way you can make changes to the library source which you must share, but you still have the freedom to link it into an iphone app without worrying that it is tainting your code with its license.

To compile as a static library is simple and to the developer simply means dragging the .a file into the xcode project and the headers which is described clearly in the sourcecode.

If another license style is required, please contact the author.