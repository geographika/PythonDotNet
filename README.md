Python for .NET
================================

This repository contains some compiled versions of the excellent Python for .NET library - http://pythonnet.sourceforge.net/

Official releases can be downloaded from http://sourceforge.net/projects/pythonnet/files/

**Update 12/2014** - the official project is now available on GitHub at https://github.com/pythonnet/pythonnet

Python for .NET is a package that gives Python programmers nearly seamless integration with the .NET Common Language Runtime (CLR) and provides a powerful application scripting tool for .NET developers. 
Using this package you can script .NET applications or build entire applications in Python, using .NET services and components written in any language that targets the CLR (Managed C++, C#, VB, JScript). 

Currently available
-------------------

The following builds are currently available. 

**/PythonDotNet202_py27_net4_x64_Windows2012**

* Python for .NET v2.0.2
* 64-bit DLLs 
* built for the .NET 4.0 Framework
* Compatible with Windows Server 2012 (and likely Windows 8)
* Python 2.7.X

**/PythonDotNet202_py26_net2_x64**

* Python for .NET v2.0.2
* 64-bit DLLs 
* built for the .NET 2.0 Framework
* Python 2.6.5

**/PythonDotNet202_py27_net4_x64**

* Python for .NET v2.0.2
* 64-bit DLLs 
* built for the .NET 4.0 Framework
* Python 2.7.2

**/PythonDotNet202_py26_net4_x32**

* Python for .NET v2.0.2
* 32-bit DLLs 
* built for the .NET 4.0 Framework
* Python 2.6.5

Installation
------------

Copy the clr.pyd and Python.Runtime.dll files in each folder to the DLLs folder in the Python installation e.g. C:\Python27\DLLs. Test the files work correctly in IDLE using the following statements: 

	>>> import clr
	>>> import System
	>>> print System.Environment.Version
	4.0.30319.239

For the .NET 2.0 versions this will be:

	>>> print System.Environment.Version
	2.0.50727.5448

See http://pythonnet.sourceforge.net/readme.html#installation for full details